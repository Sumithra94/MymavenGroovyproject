pipeline {
         agent any
         stages {
                 stage('One') {
                 steps {
                     echo 'Hi, this is Sumithra from SameTime'
                 }
                 }
                 stage('proceed') {
                 steps {
                    input('Do you want to proceed?')
                 }
                 }
                 stage('Deploy') {
                 when {
                       not {
                            branch "master"
                       }
                 }
                 steps {
                       echo "Hello"
					   
                       sh 'mvn clean build'
            
                 }
                 }
                 
              }
}