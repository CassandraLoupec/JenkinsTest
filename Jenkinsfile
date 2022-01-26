pipeline {
    agent any

    stages {
        stage('NPM Build'){
            steps {
                sh '''
                npm install
                npm start
                '''
            }
        }
    }
}
