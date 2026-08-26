pipeline{
    agent any 
    stages{
        stage('python version'){
            steps{
                sh 'python3 --version'
            }
        }
        stage('python status'){
            steps{
                sh 'python3 -m pip --version'
            }
        }
        stage('run tests'){
            steps{
                sh 'python3 app.py'
            }
        }
    }
}
