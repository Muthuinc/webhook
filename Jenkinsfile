pipeline{
    agent any

    stages{
        stage ('test') {
            steps{
                echo "dev branch"
                echo "second linee"
            }
        }
        stage ('script') {
            steps{
                sh './muthu.sh'
            }
        }
    }
}
