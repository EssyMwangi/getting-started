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
        echo 'Building....'
    }
    stage('Test') {
        echo 'Building....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}
