pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                bat 'python3 --version'
            }
        }
        stage('STAGE2'){
            steps{
                bat 'python3 python.py %X_VALUE% %Y_VALUE%'
            }
        }
    }
}
