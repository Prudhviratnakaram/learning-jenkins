pipeline {
    agent {
    node { label 'workstation' }
    }
    environment{
        SAMPLE_URL="google.com"
        SSH=credentials('SSH')
    }

    stages {
        stage('Hai') {
            steps {
                echo 'Hello World'
                echo "URL = ${SAMPLE_URL}"
                echo "${SSH}"
            }
        }
    }
    post{
        always{
            echo "I will always say hello again"
        }
    }
}
