pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'

                script {
                    def browsers =   readFile(file: 'repos.txt') 
                    
                    for (int i = 0; i < lines.size(); ++i) {
                        def lines = browsers.readLines()
                        echo "${lines}"
                    }
                }
            }
        }
    }
}
