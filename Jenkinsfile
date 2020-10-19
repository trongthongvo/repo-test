pipeline {

    //agent none
    agent {label 'slave'}

    stages {

        stage('Build') {
            steps {
                sh "chmod +x -R ${env.WORKSPACE}"
                sh '''
                    ./source/code/bash/shell.sh
                '''
            }

            
                }
            }
 
}
