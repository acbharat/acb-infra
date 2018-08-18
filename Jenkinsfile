
pipeline {
      agent any

    stages {
        stage ('Build') {
            steps {
                sh 'echo "hello world" '
                sh '''
                    echo "Multi line steps to execute"
                    ls -l
                '''
            }
        }
    }
}