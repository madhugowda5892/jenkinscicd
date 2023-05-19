pipeline {
    agent 
    {
      Docker {image 'ubuntu:latest'}
      }

    stages {
        stage('Hello') {
            steps {
                sh 'node --version'
            }
        }
    }
}
