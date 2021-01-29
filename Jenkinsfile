pipeline {
    agent any

    stages {
        stage("Read test.txt file") {
            steps {
                script {
                    def words = []
                new File( 'repos.txt' ).eachLine { line ->
                 words << line
                }

// print them out
        words.each {
             println it
}
                }
            }
        }
    }
}


