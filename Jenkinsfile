def list = [
        'PCNAME1',
        'PCNAME2',
        'PCNAME3'
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
