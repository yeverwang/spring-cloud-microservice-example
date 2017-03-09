pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "mvn package"'
                sh '''
                    echo "Multiline shell steps works too"
                    mvn package
                '''
            }
        }
    }
}
