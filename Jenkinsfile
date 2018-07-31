pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
        stage('build') {
            steps {
                sh 'php --version'
            }
        }  
        stage('test') {
            steps {
                sh 'vendor/bin/phpunit'
            }
        }
    }
}
