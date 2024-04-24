pipeline {
    agent any
    stages {
        stage ('Building') {
            steps { 
			
                bat 'mvn deploy --settings .maven/settings.xml -DmuleDeploy' 
            }            
        }

    }
}