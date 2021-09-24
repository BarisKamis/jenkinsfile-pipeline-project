pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling thethe java sds dffd source code'
                sh 'javac hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'
            }
        }
    }
}
