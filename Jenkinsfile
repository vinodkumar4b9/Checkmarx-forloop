pipeline {
   agent { label 'master' }
   stages {
       stage('read') {
           steps {
               script {
                   def list = [ readFile(file: 'repos.txt') ]
		   list.each {
                    println "${it}"
			   
		   }
               }
           }
       }
   }
}
