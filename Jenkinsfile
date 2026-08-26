pipeline{
    agent any 
    stages{
        stage('python version'){
            steps{
                sh 'python3 --version'
            }
        }
        stage('install python dependencies'){
            steps{
                sh ''
            }
        }
        stage('run tests'){
            steps{
                sh 'python3 app.py'
            }
        }
    }
}
