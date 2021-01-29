node('master') {	
	stagesWithTry([
		'Amiautomation'
		,'githubbotfdsfds'
		,'cicd-pipeline-train-schedule-jenkins'
		,'Seans-TypeScript-NodeJS-CRUD-REST-API-Boilerplate'
		,'docker-sonarqube'
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
