pipeline{
    agent any
    stages{
        stage('git clone'){
            steps{
                git credentialsId: 'c8103480-c032-4167-a9b2-5ae674340d48', url: 'https://github.com/Kavibalan1904/JenPython.git'
            }
        }
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
