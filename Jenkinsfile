/* groovylint-disable CompileStatic, DuplicateStringLiteral */
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the application..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application....'
            }
        }
    }
}
// Script //
node {
    stage('Build') {
        echo 'Building the app....'
    }
    stage('Test') {
        echo 'Building the app....'
    }
    stage('Deploy') {
        echo 'Deploying the app....'
    }
}
