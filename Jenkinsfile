pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building Java app'
          }
        }

        stage('Test') {
          steps {
            echo '"Get the driver path ${ChromeDriverPath}"'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying an App'
        input(message: 'Do you want to deploy?', id: 'OK')
      }
    }

  }
  environment {
    ChromeDriverPath = 'C:\\Users\\KKM\\Desktop\\APPIUM'
  }
}