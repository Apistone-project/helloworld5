pipeline {
    agent any
    stages {
        stage ('Building') {
            steps { 
			
                bat 'mvn deploy --settings C:/Users/326078/.m2/settings.xml -DmuleDeploy' 
            }            
        }

    }
}