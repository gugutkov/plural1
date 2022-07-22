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
                pwsh(script:'ping 8.8.8.8')
                
            }
        }
    }
}