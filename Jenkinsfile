pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'

                script {
                    def browsers =   readFile(file: 'repos.txt') 
                    def lines = browsers.readLines()
                    
                    for (int i = 0; i < lines.size(); ++i) {
                        
                        echo "${lines}"
                    }
                }
            }
        }
    }
}
