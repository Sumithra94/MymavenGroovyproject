node {

  stage ('Build') {
 
    git url: 'https://github.com/Sumithra94/MymavenGroovyproject'
	          
    withMaven(
        
        maven: 'MyMaven',
        
        sh "mvn clean install"
		
		)
    
  }
}
