pipeline {
    agent any

    stages {
        stage('Build') {
            agent {
                docker {
                    image "node:18-alphine"
                    reuseNode: true
                }
            }
            steps {
                sh '''
                    node --verison
                    npm --version

                '''
            }
        }
    }
}
