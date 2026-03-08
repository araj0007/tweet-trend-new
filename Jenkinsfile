pipeline {
    agent {
        node {
            label 'mavenagent'
        }
    }
environment {
    PATH = "/usr/share/maven/bin:$PATH"
}

    stages {
        stage('build') {
            steps {
                sh 'mvn clean install '
            }
        }
    }
}
