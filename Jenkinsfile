properties([pipelineTriggers([pollSCM('30 * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'python click.py'
                bat 'python welcome.py'
            }
        }
    }
}
