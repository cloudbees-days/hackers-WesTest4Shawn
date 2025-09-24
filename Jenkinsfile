pipeline {
  agent none
  stages {
    stage('Build') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Build Stage'
        echo 'Testing 123'
      }
    }
    stage('Dev') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Dev Stage'
        echo 'Testing 123'
      }
    }
    stage('Test') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Test Stage'
        echo 'Testing 123'
      }
    }
    stage('Prod') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Prod Stage'
        echo 'Testing 123'
      }
    }
  }
}
