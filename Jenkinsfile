@Library('my-shared-library') _

pipeline{

    agent any

    stages{

        stage('Git Checkout') {

            steps{
                gitCheckout(
                        branch: "main",
                        url: "https://github.com/khsr25/hsr_java_app.git"
                )
                }
        }

                stage('Unit Test maveen') {

            steps{
                script{
                    mvn Test()
                }
            }
        }
    }
}