pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
             script{
         
                 

##To read file from workspace which will contain the Jenkins Job Name ###
           
     def filePath = readFile "${WORKSPACE}/repos.txt"                   

##To read file line by line ###
 
     def lines = filePath.readLines() 
      
##To iterate and run Jenkins Jobs one by one ####

                    for (line in lines) {                                            
                     
                        println(lines)
                        
                        }  
                                       }
                    
         }
         }
      }
   }
