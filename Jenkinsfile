pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''sudo pip3.7 install --upgrade pip
pip install wheel
cd blogr
python3.7 setup.py bdist_wheel'''
      }
    }

  }
}