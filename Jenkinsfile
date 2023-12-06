Jenkinsfile (Declarative Pipeline) # 111dabd0c5dadaaa4cefde3f9bc92af901
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'node:20.10.0-alpine3.18' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}