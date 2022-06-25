pipeline {
    agent any
    stages {
        stage('compile') {
            steps {
              echo 'Enter Compile'
             		    
		          }
        }
        stage('build'){
            steps{
                echo 'Enter Build'
            
            }
        }
        stage('archive'){
            steps{
		sh 'rm sample.war'
		sh 'jar -cvf sample.war * ' 
                echo 'Enter Archive'
		sh 'cd /opt/tomcat/webapps'    
            }
        }
    }
}
