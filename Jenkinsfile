pipeline {
   agent { label 'master' }
   stages {
       stage('read') {
           steps {
               script {
                  
                   stagesWithTry([
                      
                      def data = readFile(file: 'repos.txt')
		                  
	])
       
               }
           }
          
       }
              
              def stagesWithTry(list){
	            for (int i = 0; i < list.size(); i++) {
		   try {	
			stage(list[i]){
			    
					
					println(list[i])
			
			} 
		} catch (Exception e) {
			echo "Stage failed, but we continue"  
		}
	}
                  
                  
               
           
       
   }
}
