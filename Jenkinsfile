pipeline {
    agent any
    tools{
        maven "maven"
    }
    stages {
        stage("compile") {
            steps {
                bat 'javac Test.java'
            }
        }

        stage("run") {
            steps {
                bat 'java Test'
            }
        }
    }
}