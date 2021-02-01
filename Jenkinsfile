pipeline {
   agent { label 'master' }
   stages {
       stage('read') {
           steps {
               script {
                   def list = [ readFile(file: 'repos.txt') ]
		   for (item in list) {
   				println item
			        sh "echo required Item is $item"
			}
		   
               }
           }
       }
   }
}


