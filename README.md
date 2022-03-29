pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'builiding'
            }
        }
        stage('Depoly') {
            steps {
                echo 'deploying'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('deliver') {
            steps {
                echo 'delivered'
            }
        }
    }
}
