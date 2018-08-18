#Jenkins pipeline (multi branch)

pipeline {
    agent { docker {image 'maven 3.3.3'} }

    stages {
        stage ('Build') {
            steps {
                sh 'mvn -v-version'
            }
        }
    }
}