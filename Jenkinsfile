pipeline {
   agent { label 'master' }
   stages {
       stage('read') {
           steps {
               script {
                   def x = [ readFile(file: 'repos.txt') ]
		   println(x)
		   
               }
           }
       }
   }
}
