pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                echo "Building the project..."
                // build steps go here
            }
        }
        stage("Test") {
            steps {
                echo "Testing the project..."
                // test steps go here
            }
        }
        stage("Deploy") {
            when {
                changeRequest targetBranch: "Alex"
            }
            steps {
                echo "there is a change in the branch ALEX"
             
            }
        }
    }
}
