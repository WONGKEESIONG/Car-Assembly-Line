pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            dir(path: 'C:/Users/sqkswong/Downloads/Jenkins/build.bat')
            bat 'C:/Users/sqkswong/Downloads/Jenkins/build.bat'
          }
        }

        stage('Test') {
          steps {
            echo 'Test ok'
          }
        }

      }
    }

    stage('Test') {
      steps {
        dir(path: 'C:/Users/sqkswong/Downloads/Jenkins/test.bat')
        bat 'C:/Users/sqkswong/Downloads/Jenkins/test.bat'
      }
    }

    stage('Publish') {
      steps {
        dir(path: 'C:/Users/sqkswong/Downloads/Jenkins/publish.bat')
        bat 'C:/Users/sqkswong/Downloads/Jenkins/publish.bat'
      }
    }

  }
}