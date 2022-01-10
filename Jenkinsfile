pipeline {
    agent  any;
    stages {
        stage('Preparing the environment') {
            steps {
                sh 'echo Preparing the env'
            }
        }
        stage('Code Quality') {
            steps {
                sh 'echo Checking code quality'
            }
        }
        stage('Tests') {
            steps {
                sh 'echo Testing the Applications'
            }
        }
   
    stage('Build') {
          steps {
              sh 'echo Creating application Package'
          }
      }        
      stage('Deploy') {
          steps {
              sh 'echo Deploying the Application'
          }
      }
    }

}
