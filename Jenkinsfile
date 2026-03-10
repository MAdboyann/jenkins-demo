pipeline {
    agent any

    stages {

        stage('Clone Info') {
            steps {
                echo 'Code pulled from GitHub successfully'
            }
        }

        stage('Check Files') {
            steps {
                sh 'ls -la'
            }
        }

        stage('Run Script') {
            steps {
                sh 'chmod +x app.sh'
                sh './app.sh'
            }
        }

    }
}
