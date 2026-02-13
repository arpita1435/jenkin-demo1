pipeline {
  agent any

  stages {
    stge('clone') {
      steps {
        echo 'Cloning repository...'
      }
    }

    stage('install') {
      steps {
        sh 'npm install'
      }
    }

    stage('run') {
      steps {
        sh 'npm start'
      }
    }
  }
}



  
