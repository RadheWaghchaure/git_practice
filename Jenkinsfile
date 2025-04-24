pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/RadheWaghchaure/PowerShell.git'
            }
        }

        stage('Run PowerShell Script') {
            steps {
                powershell './your-script.ps1'  // Change this to your actual script filename
            }
        }
    }
}
