pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'pip install -r requirements.txt'
                
            }
        }
        stage('deploy'){
            steps{
                sh 'nohup app.py &'
          }
      }
    }
}
