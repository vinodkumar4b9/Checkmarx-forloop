pipeline {
    agent any

    stages {
        stage("Read test.txt file") {
            steps {
                script {
                    final String content = readFile(file: "repos.txt")
                    final List myKeys = extractLines(content)
                    echo "${myKeys}"
                }
            }
        }
    }
}

@NonCPS
List extractLines(final String content) {
    List myKeys = []
    content.eachLine { line -> 
        myKeys << line
    }
    return myKeys
}
