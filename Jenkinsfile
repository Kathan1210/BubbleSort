pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac BubbleSortExample.java'
            }
        }
        stage('Run') {
            steps {
                bat 'java BubbleSortExample'
            }
        }
    }
}
