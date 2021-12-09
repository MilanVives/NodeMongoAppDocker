pipeline {

    agent docker

    stages {
      stage(‘Build’) {
        steps {
          sh 'docker-compose up --build'
        }
      }
    }
}