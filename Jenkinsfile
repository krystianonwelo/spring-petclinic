library 'zadanie-jenkins'
pipeline {
    agent none
    stages {
        stage('pipelineMaven') {
            agent { label  'slave-node' }
            steps {
                pipelineMaven([skipTests: 0, skipInstallingArtifacts: 1], 'sdsdada')
            }
        }
    }
}
