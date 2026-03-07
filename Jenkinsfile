pipeline {
    agent {
        node {
            label 'rajmaven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', credentialsId: 'maven-server', url: 'https://github.com/araj0007/tweet-trend-new.git'
            }
        }
    }
}
