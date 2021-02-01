pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
             script{
         
                 
           
     def filePath = readFile "${WORKSPACE}/repos.txt"                   

 
     def lines = filePath.readLines() 
      


                    for (line in lines) {                                            
                     
                        println(lines)
                        
                        }  
                                       }
                    
         }
         }
      }
   }
