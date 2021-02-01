pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
             script {
                   def data = readFile(file: 'repo.txt')
                   println(data)
               }
         }
         }
      }
   }
