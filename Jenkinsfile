pipeline {
    agent any
    tools {
        nodejs "nodejs"
    }
    stages {
        stage('build')
        {
            steps {
        sh 'pwd'
                sh 'npm install'
                sh 'pm2 update'
                sh 'pm2 start -f index.js'
                sh 'pwd'
sh 'pm2 list'
         echo "pm2 service starte"
        
        }
    }
}
}
