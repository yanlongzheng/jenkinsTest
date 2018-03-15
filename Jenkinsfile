pipeline {
//    agent { docker { image 'python:3.5.1' } }
    agent any
    stages {
        stage('build') {
            steps {
                sh 'g++ -o test ./test.cpp'
            }
        }
        stage('test') {
            steps {
                sh './test'
            }
        }
    }
}
