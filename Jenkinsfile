pipeline {

    agent any

    stages {
      stage(‘Build’) {
        steps {
          /*sh 'docker-compose up --build'*/
          sh '''
          docker --version
          docker compose version
            '''
        }
      }
    }
}