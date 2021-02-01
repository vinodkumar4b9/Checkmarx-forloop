
pipeline {
    agent any

    stages {
        stage('Loop through PCs') {
            def list =  readFile(file: 'repos.txt')
            steps {
                loopPC(list)
            }
        }
    }
}

def loopPC(list){
    list.each {
        println "Computer ${it}"
    }
}
