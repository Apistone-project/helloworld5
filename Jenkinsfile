pipeline {
    agent any
    stages {
        stage ('Building') {
            steps { 
			
                bat 'mvn clean deploy -DmuleDeploy' 
            }            
        }

    }
}