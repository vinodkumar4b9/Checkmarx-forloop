node('master') {	
	stagesWithTry([
		
      def list = readFile(file: 'repos.txt')
     
	])
}

def stagesWithTry(list){
	for (int i = 0; i < list.size(); i++) {
			
			stage(list[i]){
					sh "git clone https://github.com/vinodkumar4b9/${list[i]}.git"
		
		 
	}
}
