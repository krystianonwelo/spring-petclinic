library 'zadanie-jenkins'
pipeline {
    agent none
    stages {
        stage('pipelineMaven') {
            agent { label  'slave-node' }
                pipelineMaven()
        }
    }
}
