pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        echo 'pwd'
     // }
   // }

    stage('Build') {
      steps {
        echo 'pwd'
      }
    }

    stage('Test') {
      steps {
        echo 'pwd'
      }
    }

    stage('Deploy in Production') {
      steps {

        timeout(time: 2, unit: 'MINUTES') {
          input(message: 'Do you want to approve the deployment , please approve ?', ok: 'Yes')
        }
        
        echo 'pwd'
        echo 'Initiating deployment'
        
      }
    }

  }
}
