pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
             script{
      def filePath = readFile "${WORKSPACE}/dest_hosts.txt"                   
      def lines = filePath.readLines() 
      def tagspath = readFile "${WORKSPACE}/dest_hosts.txt"                   
      def tags = tagspath.readLines()
      lines.each { String line ->
        sh "echo $line"
      }
      tags.each { String tag ->
               sh "echo $tag"
               sh "echo $line"
               
         }
                     
                                       }
                    
         }
         }
      }
   }
