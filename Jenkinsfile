pipeline {
    agent {
        dockerfile {
            dir 'docker/browsers'
        }
    }
    stages {
        stage('Example Build') {
            steps {
                echo 'echo something'
            }
        }
    }
}