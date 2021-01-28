node('master') {	
	stagesWithTry([
		
       	def filePath = readFile "${WORKSPACE}/ repos.txt" 
	def list = filePath.readLines()
     
	])
}

def stagesWithTry(list){
	for (int i = 0; i < list.size(); i++) {
			
			stage(list[i]){
					sh "git clone https://github.com/vinodkumar4b9/${list[i]}.git"
		
		 
	}
  }
}
