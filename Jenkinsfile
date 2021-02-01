def list = [
        
        readFile(file: 'repos.txt')
]

pipeline {
    agent any

    stages {
        stage('Loop through PCs') {
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
