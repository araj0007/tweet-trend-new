pipeline {
    agent {
        node {
            label 'rajmaven'
        }
    }
environment {
    PATH = "/usr/share/maven/bin:$PATH"
}

    stages {
        stage('build') {
            steps {
                sh 'mvn deploy '
            }
        }
    }
}
