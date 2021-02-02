pipeline {
    agent any
    stages {
        stage('Example') {
            steps {

                script {
                    def browsers =   readFile(file: 'repos.txt') 
                    loop_of_sh(abcs)
                    
                    
                    }
                }
            }
        }
    }


@NonCPS
def loop_of_sh(list) {
    list.each { item ->
        sh "echo Hello ${item}"
    }
}
