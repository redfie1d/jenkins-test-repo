pipeline {
    agent any
    
    tools {
        node 'Node-15.14'
    }

    stages {
        stage('run frontend') {
            steps {
                echo 'executing yarn...'
                sh 'yarn install'
            }
        }
    }
}
