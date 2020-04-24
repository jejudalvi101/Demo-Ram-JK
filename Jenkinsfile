pipeline {
    agent  {
    label 'Ubuntu_WorkerNode1'
    }
        stages {
            stage('Build') {
                steps {
                    sh 'mvn package'
                }
            }
            stage('Test') {
                  steps {
                    echo 'Testing..'
                }
            }
            stage('Deploy') {
                steps {
                    echo 'Deploying....'
                    }
                }
         }
     }
