pipeline { 
    agent any
    stages {
        stage('Clone') {
            steps {
                sh "rm -rf *"
                sh "git clone https://github.com/KraimABD/test.git"
            }
        }

        stage('Build') {
            steps {
                sh "cd test / && javac Main.java"

            }
        }

        stage('Run') {
            steps {
                sh "cd test / && java Main"
            }
        }
    }
}
