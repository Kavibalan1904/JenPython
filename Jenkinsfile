pipeline{
    agent any
    stages{
        stage('git clone'){
            steps{
                git credentialsId: 'c8103480-c032-4167-a9b2-5ae674340d48', url: 'https://github.com/Kavibalan1904/JenPython.git'
            }
        }
        stage('python install'){
            steps{
                sh 'sudo apt install python3-pip'
            }
        }
        stage('python version'){
            steps{
                sh 'python3 --version'
            }
        }

        }
        stage('run tests'){
            steps{
                sh 'python3 app.py'
            }
        }
    }
