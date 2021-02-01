pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
             script{
         
                 
                for repo in $(cat repos.txt)  {
               echo "$repo" 
            done
                }
                                       }
                    
         }
         }
      }
   }
