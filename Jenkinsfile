node ("windows"){

  stage ('Build') {
 
    git url: 'https://github.com/Sumithra94/MymavenGroovyproject'
	          
    withMaven(
        
        maven: 'MyMaven',
        
        bat "mvn clean install"
    
  }
}