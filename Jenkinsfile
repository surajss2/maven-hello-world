pipeline{
    agent any 
    stages{
        stage ('Build'){
            steps{
                mvn clean compile
            }

        }
        stage ('packages'){
            steps{
                mvn Package
            }

        }
        
    }
}
