pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                sh '"c:\\Windows\\System32\\cmd.exe" /c python --version'
            }
        }
        stage('STAGE2'){
            steps{
                sh '"c:\\Windows\\System32\\cmd.exe" /c python python.py %X_VALUE% %Y_VALUE%'
            }
        }
    }
}
