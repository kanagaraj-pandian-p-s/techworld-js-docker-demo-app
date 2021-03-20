pipeline {
    agent any
    stages {
        stage("init") {
            steps {
                echo "initializing..."
            }
        }
        stage("build jar") {
            steps {
                echo "building jar"
             }
        }
        stage("build image") {
            steps {
                echo "building docker image"
             }
        }
        stage("deploy") {
            steps {
                echo "deploying..."
             }
        }
    }   
}
