pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
             script{
      def filePath = readFile "${WORKSPACE}/dest_hosts.txt"                   
      def lines = filePath.readLines() 
      lines.each { String line ->
      // sh "echo $line"
         def tagPath = readFile "${WORKSPACE}/vinod.txt"                   
         def tags = tagPath.readLines()
         tags.each { String tag ->
            sh "echo $line"
            sh "echo $tag"
            
         }
            
              
               
        
      }
      
                     
                                       }
                    
         }
         }
      }
   }
