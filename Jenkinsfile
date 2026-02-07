pipeline {
    agent any

    tools {
        nodejs 'nodejs'   // Jenkins > Global Tool Configuration ch NodeJS name
    }

    environment {
        NODE_ENV = 'any'
    }

    stages {

        stage('Checkout Code') {
            steps {
                git branch: 'master',
                    url: 'https://github.com/eshuramgarhia/backend-tour123.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
  
            }
        }

        pipeline {
    agent any

    environment {
        NODE_ENV = 'any'
    }

    stages {

        stage('Checkout Code') {
            steps {
                git branch: 'master',
                url: 'https://github.com/eshuramgarhia/backend-tour123.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Run Tests') {
            steps {
                bat 'echo Tests skipped'
            }
        }
    }
}

            }
        }

    }
  }
