pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
             script{
      def filePath = readFile "${WORKSPACE}/dest_hosts.txt"                   
      def lines = filePath.readLines() 
      lines.each { String line ->
        
         sh "echo $line"      
        
      }
                    }
         }
      }
   }
