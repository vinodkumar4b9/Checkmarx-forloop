pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
             script {
                   def data = readFile(file: 'repos.txt')
                   println(data)
               }
         }
         }
      }
   }
