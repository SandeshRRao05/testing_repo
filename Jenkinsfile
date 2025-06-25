pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'Jenkins1.0', url: 'https://github.com/SandeshRRao05/testing_repo.git'
            }
        }

        stage('Run Script') {
            steps {
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }
    }
}

