pipeline{
    agents any

    stages{
        stage('stage 1') {
            steps{
                echo "This is my first pipeline"
                echo "This is checkout stage"
                checkout scmGit(branches: [[name: '*/main']],
                extensions: [],
                userRemoteConfigs: [[credentialsId: 'my_id',
                url: 'https://github.com/vinayak4393/Jenkins_pipelines.git']])

            }
        }
    }
}