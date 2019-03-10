#!/usr/bin/env groovy

pipeline {

    agent {
        docker {
            image 'node'
            args '-u root'
        }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                exit 0
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                exit 0
            }
        }
    }
}
