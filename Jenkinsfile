pipeline{
    agent any

    stages{
        stage ('test') {
            steps{
                echo "dev branch"
                echo "second line"
            }
        }
        stage ('script') {
            steps{
                sh './muthu.sh'
            }
        }
    }
}
