pipeline {
    agent any
    stages{
        stage('Verify Branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage('Docker Build'){
            steps{
                sh('pwsh ping 8.8.8.8')
                
            }
        }
    }
}