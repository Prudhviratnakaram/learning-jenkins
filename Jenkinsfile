pipeline {
    agent {
    node { label 'workstation' }
    }

    stages {
        stage('Hai') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post{
        always{
            echo "I will always say hello again"
        }
    }
}
