pipeline {
    agent any

    tools {
        maven 'Maven'
    }

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
