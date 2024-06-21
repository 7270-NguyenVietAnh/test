pipeline {
    agent any
    stages {
        stage('Clone repository') {
            steps {
                git url: 'https://github.com/7270-NguyenVietAnh/test.git'
            }
        }
        stage('Build') {
            steps {
                bat 'build.bat'
            }
        }
    }
}