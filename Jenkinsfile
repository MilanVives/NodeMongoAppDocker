pipeline {

    agent any

    stages {
      stage(‘Build’) {
        steps {
          /*sh 'docker-compose up --build'*/
          sh '''
            apt update && apt install docker docker-compose
            docker --version
            docker compose version
            '''
        }
      }
    }
}