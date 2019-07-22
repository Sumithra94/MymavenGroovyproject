node(){
 	def mavenHome=tool name: "MVN_HOME", type: "maven"
 	 
 	stage('building the onlineshoping artifactBuild')
 	{
 	sh "${MVN_HOME}/bin/mvn clean package"
 	}
	
