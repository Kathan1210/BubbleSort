pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat "javac BubbleSort/BubbleSortExample.java"
            }
        }
        stage('Run') {
            steps {
                bat "java BubbleSort/BubbleSortExample"
            }
        }
    }
}
