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
                PowerShell(". '.\\disk-usage.ps1'; du -Verbose")
                
            }
        }
    }
}