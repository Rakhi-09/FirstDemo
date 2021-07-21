pipeline {
    agent any
    options { overrideIndexTriggers(false)}
    
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
