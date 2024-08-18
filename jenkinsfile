pipeline {
    agent {label 'Built-In Node'}

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
