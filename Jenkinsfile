pipeline {
    agent any
    stages {
       stage("Checking Docker Version in master") {
            steps {
                {
                sh "docker --version"
                }
            }
        }
        stage("Checking GIT Version in master") {
            steps {
                sh "git --version"
            }
        }
        stage("branch Alex") {
            when {
                branch "Alex"
            }
            steps {
                echo "running in branch Alex"
                
            }
        }
    }
}
