pipeline {
    agent 
    {
      docker {image 'ubuntu:latest'}
      }

    stages {
        stage('first') {
            steps {
                sh 'ls -l'
            }
        }
    }
}
