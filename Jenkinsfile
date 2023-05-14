@Library(my-shared-libary)

pipeline{

    agent any

    stages{

        stage('Git Checkout') {

            steps{

                script{

                    gitCheckout(
                        branch: "main"
                        url: "https://github.com/khsr25/hsr_java_app.git"
                    )
                }
            }
        }
    }
}