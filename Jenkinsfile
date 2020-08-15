pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pip install wheel
cd blogr
python3.7 setup.py bdist_wheel'''
      }
    }

  }
}