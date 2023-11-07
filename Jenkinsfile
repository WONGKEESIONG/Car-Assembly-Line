pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                dir('C:/Users/sqkswong/Downloads/build.bat'){
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqkswong/Downloads/build.bat'
            }
        }
        stage('Test') {
            steps {
                dir('C:/Users/sqkswong/Downloads/test.bat'){
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqkswong/Downloads/test.bat'
            }
        }
        stage('Publish') {
            steps {
                dir('C:/Users/sqkswong/Downloads/publish.bat'){
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqkswong/Downloads/publish.bat'
            }
        }
    }
}
