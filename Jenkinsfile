pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hello1') {
            steps {
                echo "hello"
            }    
        }
        stage('SH') {
            steps {
                sh bash run.sh
            }    
        }
    }
}
