pipeline{
    agent any 
    stages{
        stage ('Build'){
            steps{
                sh mvn clean compile
            }

        }
        stage ('packages'){
            steps{
                sh mvn Package
            }

        }
        stage ('Deploy'){
            steps{
                sh cp /var/lib/jenkins/workspace/Myfirst_Pipeline_project/target/ /home/suraj/opt/tomcat/webapps/
            }

        }
    }
}
