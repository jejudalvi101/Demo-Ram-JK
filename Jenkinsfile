pipeline {
    agent {
        label any
        }
        stages {
            stage('Build on worker 1') {
                steps {
                    sh 'mvn package'
                }
            }
            stage('Test on master') {
                agent{
                    label any
                }
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
