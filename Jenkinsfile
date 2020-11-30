#!/usr/bin/env groovy

pipeline {
    agent { node { label 'worker_node1' } }
    
    stages {
        stage("Test") {
            steps {
                echo "print env variable"
                sh "printenv"
            }
        }
}
