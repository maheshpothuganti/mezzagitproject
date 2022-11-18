pipeline {
    agent any
    stages {
        stage("git clone repo") {
            steps{
                echo "cloning git repository"
            }
        }
        stage("maven build") {
            steps{
                echo "building artifact"
            }
        }
        stage("deply stage") {
            steps{
                echo "deploy artifact to server"
            }
        }
    }
}
