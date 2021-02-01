pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
             script {
                   def data = readFile(file: 'zorg.txt')
                   println(data)
               }
         }
         }
      }
   }
