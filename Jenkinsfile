pipeline {
   agent { label 'master' }
   stages {
       stage('read') {
           steps {
               script {
                   def x = readFile(file: 'repos.txt')
                   println(x)
		   for (int i = 0; i < x.size(); i++) {
			  
			   println(i)
			   
		   }
               }
           }
       }
   }
}
