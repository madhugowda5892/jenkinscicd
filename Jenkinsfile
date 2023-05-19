pipeline {
    agent 
    {
      docker {image 'ubuntu:latest'}
      }

    stages {
        stage('Hello') {
            steps {
                sh 'node --version'
            }
        }
    }
}
