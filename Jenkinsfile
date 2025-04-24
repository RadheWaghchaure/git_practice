pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
               echo hello
            }
        }

        stage('Run PowerShell Script') {
            steps {
                powershell './your-script.ps1'  // Change this to your actual script filename
            }
        }
    }
}
