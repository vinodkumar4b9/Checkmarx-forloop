pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
             script{
      def filePath = readFile "${WORKSPACE}/dest_hosts.txt"                   
      def lines = filePath.readLines() 
      lines.each { String line ->
              def tagspath = readFile "${WORKSPACE}/dest_hosts.txt"                   
               def tags = tagspath.readLines()  
         tags.each { String tag ->
               sh "echo $tag"
               sh "echo $line"
         }
                     }
                                       }
                    
         }
         }
      }
   }
