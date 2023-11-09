pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                dir('C:/Users/sqkswong/Downloads/Jenkins/build.bat'){
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqkswong/Downloads/Jenkins/build.bat'
            }
        }
        stage('Test') {
            steps {
                dir('C:/Users/sqkswong/Downloads/Jenkins/test.bat'){
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqkswong/Downloads/Jenkins/test.bat'
            }
        }
        stage('Publish') {
            steps {
                dir('C:/Users/sqkswong/Downloads/Jenkins/publish.bat'){
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqkswong/Downloads/Jenkins/publish.bat'
            }
        }
    }
}
