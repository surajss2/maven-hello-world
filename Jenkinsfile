pipeline{
    agent any 
    stages{
        stage ('Build'){
            steps{
                sh 'mvn clean compile'
            }

        }
        stage ('packages'){
            steps{
                sh 'mvn package'
            }

        }
        
    }
}
