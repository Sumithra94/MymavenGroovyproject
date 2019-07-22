node {

  stage ('Build') {
 
    git url: 'https://github.com/Sumithra94/MymavenGroovyproject'
	          
    withMaven(
        
        maven: 'MVN_HOME',
        
        sh "mvn clean install"
		
		)
    
  }
}
