pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh(script: """
                echo "hello"
                docker build .
                """)      
            }
        }
    }
}
