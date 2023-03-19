pipeline {
    agent any

    stages {
        stage('Pwd') {
            steps {
                sh 'pwd'
            }
        }
        stage('Build') {
            steps {
                sh "javac BubbleSort/BubbleSortExample.java"
            }
        }
        stage('Run') {
            steps {
                sh "java BubbleSort/BubbleSortExample"
            }
        }
    }
}
