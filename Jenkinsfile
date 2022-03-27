pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo "This is a build $BUILD_NUMBER with demo as $DEMO"
      }
    }

  }
  environment {
    DEMO = '1'
  }
}
