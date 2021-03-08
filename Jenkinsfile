pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
             script{
            


           
     def filePath = readFile "${WORKSPACE}/dest_hosts.txt"                   
      def lines = filePath.readLine() 
      


                    for (line in lines) 
                 
                        sh "echo $lines"
                                       }
                    
         }
         }
      }
   }
