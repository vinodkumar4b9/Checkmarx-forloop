pipeline {
   agent { label 'master' }
   stages {
       stage('read') {
           steps {
               script {
                   def list = [ readFile(file: 'repos.txt') ]
		  for (int i = 0; i < list.size(); i++) {
				sh "echo Test Var ${list[i]}"
			}
		   
               }
           }
       }
   }
}


