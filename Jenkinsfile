pipeline {
    agent any

    stages {
        stage('Welcome') {
          steps {
            sh 'Hello from Jenkins'
          }
        }
        stage('Build') {
            steps {
                sh 'javac BubbleSortExample.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java BubbleSortExample'
            }
        }
    }
}
