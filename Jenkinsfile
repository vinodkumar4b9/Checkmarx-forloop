pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
             script{
         
                 
            for repo in $(cat repos.txt); do
               echo "$repo" 
            done
                                       }
                    
         }
         }
      }
   }
