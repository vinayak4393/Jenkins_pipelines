pipeline{
    agent any

    stages{
        stage('stage 1') {
            steps{
                echo "This is checkout stage"               
            }
        }
        stage('stage 2') {
            steps{               
                echo "This is build stage"
                sleep 10   
            }
        }
    }
}