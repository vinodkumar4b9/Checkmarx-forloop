pipeline {
   agent { label 'master' }
   stages {
       stage('read') {
           steps {
               script {
                   def list =  readFile(file: 'repos.txt') 
                   map.each { entry ->
                        stage (entry.key) {
                    echo "$entry.value"

        }
		  
		   
               }
           }
       }
   }
}


