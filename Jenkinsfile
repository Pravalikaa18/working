pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/Pravalikaa18/working.git'
            }
        }

        stage('Compile') {
            steps {
                sh 'javac Palindrome.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Palindrome'
            }
        }
    }
}
