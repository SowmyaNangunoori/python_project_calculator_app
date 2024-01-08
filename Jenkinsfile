pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'pip install -r requirements.txt'
                
            }
        }
      stage('deploy'){
        sh 'python3 calculator_app.py'
      
      }
    }
}
