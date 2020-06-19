pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                powershell 'echo "Hello World"'
                powershell '''
                    echo "Multiline shell steps works too"
                    pwd
                '''
            }
        }
    }
}
