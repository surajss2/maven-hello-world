pipeline{
    agent any 
    stages{
        stage ('source code checkout'){
            steps{
                echo"git code checkout"
            }
        }
        stage ('Build'){
            steps{
                echo"mvn clean install"
            }

        }
        stage ('Test'){
            steps{
                echo "testing"
            }

        }
        stage ('Deploy'){
            steps{
                echo"mvn deploy"
            }

        }
    }
}