pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'touch NewFile.txt'
                sh 'echo "this is a content of a NewFile" >> NewFile.txt'
                }
            }
        stage('test') {
            steps {
                sh 'cat NewFile.txt'
                }
            }
        stage ('deploy') {
            steps {
                sh 'echo "Success"'
                }
            }
        }
    }
