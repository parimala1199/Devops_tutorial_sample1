pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/parimala1199/Devops_tutorial_sample1.git'
            }
        }

        stage('Hello') {
            steps {
                echo "Hello from Jenkins Pipeline!"
            }
        }

        stage('Goodbye') {
            steps {
                echo "Pipeline finished successfully 🚀"
            }
        }
    }
}
