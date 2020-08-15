pipeline {
  agent {
    docker {
      image 'python:3.7.2'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh '''pwd
pip install wheel pytest coverage
cd blogr
python3.7 setup.py bdist_wheel
cd ..
pytest'''
      }
    }

  }
}