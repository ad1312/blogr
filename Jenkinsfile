pipeline {
  agent any
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