pipeline {
    agent any

    stages {
        stage('NPM Build'){
            steps {
                sh '''
                set +e
                export PATH=/sbin:/usr/sbin:/bin:/usr/bin:/usr/local/bin/
                npm install
                npm start
                '''
            }
        }
    }
}
