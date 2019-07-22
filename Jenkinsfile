node(){
 	def mavenHome=tool name: "MVN_HOME", type: "maven"
 	 
 	stage('Build'){
 	if(isUnix()){
 	sh 'mvn clean package'
 	}else{
 	bat 'mvn clean package'
 	}
 	}
	
}
	
