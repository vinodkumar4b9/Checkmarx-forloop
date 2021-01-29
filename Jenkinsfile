pipeline {
   agent { label 'master' }
   stages {
       stage('read') {
           steps {
               script {
                   def x = readFile(file: 'repos.txt')
                   println(x)
		   for (int i = 0; i < z.size(); i++) {
			  
			   println(i)
			   
		   }
               }
           }
       }
   }
}
