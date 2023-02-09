pipeline {
    agent any
    stages {
      pipeline {
    agent any

    stages {
        stage("Checking Docker Version") {
            when {
                branch "master"
            }
            steps {
                sh 'docker --version'
            }
        }
        stage("Checking python Version") {
            when {
                branch "master"
            }
            steps {
                sh 'pyhton3 --version'
            }
        }
        stage("checking docker images") {
            when {
                branch "Alex"
            }
            steps {
                echo "docker images"
                
            }
         }
        } 
      }
    }
}
