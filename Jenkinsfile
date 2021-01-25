node('master') {	
	stagesWithTry([
		'https://github.com/vinodkumar4b9/Amiautomation.git'
		,'https://github.com/vinodkumar4b9/githubbotfdsfds.git'
		,'https://github.com/vinodkumar4b9/cicd-pipeline-train-schedule-jenkins.git'
		,'https://github.com/vinodkumar4b9/Seans-TypeScript-NodeJS-CRUD-REST-API-Boilerplate.git'
		,'https://github.com/vinodkumar4b9/docker-sonarqube.git'
	])
}

def stagesWithTry(list){
	for (int i = 0; i < list.size(); i++) {
		try {	
			stage(list[i]){
					sh "git clone  ${list[i]}"
					
			} 
		} catch (Exception e) {
			echo "Stage failed, but we continue"  
		}
	}
}
