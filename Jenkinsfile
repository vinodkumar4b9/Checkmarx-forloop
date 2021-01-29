node('master') {	
	stagesWithTry([
		
		load "${WORKSPACE}/repos.txt
	])
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
