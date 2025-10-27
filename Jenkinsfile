pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/YOUR_USERNAME/api-fetch.git'
            }
        }
        stage('Build HTML') {
            steps {
                bat 'dir'
            }
        }
        stage('Display Link') {
            steps {
                script {
                    echo "✅ API Fetch Project Ready!"
                    echo "<a href='file:///C:/ProgramData/Jenkins/.jenkins/workspace/${env.JOB_NAME}/api-fetch.html' target='_blank'>Open API Fetch</a>"
                }
            }
        }
    }
}
