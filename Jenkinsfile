pipeline {
   agent { label 'master' }
     stages {
       stage('read') {
           steps {
               script {
                   def data = readFile(file: 'repos.txt')
                   println(data)
               }
           }
       }
   }
}
