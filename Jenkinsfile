pipeline {
    agent any
    options { overrideIndexTriggers(true)}
    triggers {
        pollSCM('H/2 * * * *')
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
