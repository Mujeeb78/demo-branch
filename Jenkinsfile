pipeline {
    agent any

    stages {
        stage("Build") {
            when {
                branch "master"
            }
            steps {
                echo "Building the project..."
                // build steps go here
            }
        }
        stage("Test") {
            when {
                branch "master"
            }
            steps {
                echo "Testing the project..."
                // test steps go here
            }
        }
        stage("Deploy") {
            when {
                branch "Alex"
            }
            steps {
                echo "Deploying the project..."
                // deploy steps go here
            }
        }
    }
}
