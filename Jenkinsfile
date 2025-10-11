pipeline {
    tools {
	nodejs "NodeJS_18"
          }
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
