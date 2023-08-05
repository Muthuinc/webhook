pipeline{
    agent any

    stages{
        stage ('test') {
            steps{
                echo "dev branch"
                echo "second line"
            }
        }
        stage ('test') {
            steps{
                sh './muthu.sh'
            }
        }
    }
}
