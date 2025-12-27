pipeline {
    agent any

    stages {
/*         stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        } */
        stage('Unit Test') {
            steps {
                echo "Unit testing is done here"
            }
        }
        //sonar-scanner expects sonar-project.properties
        stage('sonar scan') {
            steps {
                sh 'ls -lrt'
                sh 'sonar-scanner'
            }
        }
    }
}