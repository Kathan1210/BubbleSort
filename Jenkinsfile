pipeline {
    agent any

    stages {
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
