pipeline {
    agent {
        label 'Jenkins_Ubuntu_Agent1'
        }
        stages {
            stage('Build on worker 1') {
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
