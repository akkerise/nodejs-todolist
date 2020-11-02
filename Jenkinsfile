pipeline {
    agent {label 'aruze-slave1'}
    stages {
        stage('1.Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('2.Clone') {
            steps {
                git 'https://github.com/akkerise/nodejs-todolist.git'
            }
        }
    }
}
