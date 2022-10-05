pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/Chris-Morris/python_jenkins_test', branch: 'main'
            }
        }
        stage('Run script') {
            steps {
                echo "Hello world!!!"
            }
        }
    }
}
