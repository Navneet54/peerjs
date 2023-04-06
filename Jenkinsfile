pipeline {
    agent any
    tools {
        nodejs "nodejs"
    }
    stages {
        stage('Hello') {
            steps {
                sh 'npm install'
                sh 'pm2 start index.js'
                sh 'pm2 list'
                echo "this is list"
            }
        }
    }
}
