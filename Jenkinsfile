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
        stage ('Deploy on tomat server'){
            steps{
                sh 'cp /var/lib/jenkins/workspace/Myfirst_Pipeline_project/target/ /opt/tomcat/webapps/'
            }

        }
    }
}
