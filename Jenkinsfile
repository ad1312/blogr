pipeline {
  agent {
    docker {
      image 'python:3.7.2'
    }

  }
  stages {
    stage('Build') {
      steps {
        script {
          pip install wheel
          cd blogr
          python setup.py bdist_wheel
        }

      }
    }

  }
}