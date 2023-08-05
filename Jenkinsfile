pipeline{
    agent any

    stages{
        stage ('test') {
            steps{
                echo "master branch"
                echo "second line"
            }
        }

        stage ('test') {
            steps{
                sh ' ./muthu.sh '
            }
        }
    }
}
