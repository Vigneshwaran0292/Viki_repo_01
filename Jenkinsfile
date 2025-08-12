pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                gt '"c:\\Windows\\System32\\cmd.exe" /c python3 --version'
            }
        }
        stage('STAGE2'){
            steps{
                gt '"c:\\Windows\\System32\\cmd.exe" /c python python.py %X_VALUE% %Y_VALUE%'
            }
        }
    }
}
