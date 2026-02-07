pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'develop', url: 'https://github.com/Bharani-dharan-k/gitflow-jenkins-ci.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building... (Simulating Compilation)'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing... (Simulating Unit Tests)'
            }
        }
    }
}
