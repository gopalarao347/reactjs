pipeline {
    agent any
    environment{
        // Sonar Project Info - You must replace these vars with the Project Name and Key from the ADOP Portal!
        SONAR_PROJECT_NAME = 'Simple Java project analyzed with the SonarQube Runner'
        SONAR_PROJECT_KEY = 'java-sonar-runner-simple'
        ENVIRONMENT_NAME = 'CI'
        }
    stages{
        stage("Reference Application Build"){
            steps{
                echo "Hellow World"
				bat 'node --version'
            }
        }   
    }
}