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
		sh 'jar -cvf sample.war * ' 
                echo 'Enter Archive'
            }
        }
    }
}
