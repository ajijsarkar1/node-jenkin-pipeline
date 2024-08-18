pipeline {
    agent {label 'agentlinux'}

    stages {
        stage('check version') {
            steps {
                // Checkout the code from version control
                sh "node --version"
                sh "npm --version"
            }
        }       
    }
}
