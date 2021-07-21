pipeline {
    agent any
    options { overrideIndexTriggers(false)}
    triggers {
        pollSCM('H/1 * * * *')
    }
    stages {
        stage('Compiling Stage!!!') {
            steps {
                sh "javac Helloo.java"
            }
        }
        stage('Running Stage') {
            steps {
                sh "java Helloo"
            }
        }
    }
}
