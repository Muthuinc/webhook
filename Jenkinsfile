pipeline{
    agent any

    stages{
        stage ('test') {
            steps{
                echo "master branch"
                echo "second line"
            }
        }

        stage ('script') {
            steps{
                sh ' ./muthu.sh '
            }
        }
    }
}
