pipeline{

    agent any

    stages{

        stage('Git Checkout') {

            steps{

                script{

                    git branch: 'main', url: 'https://github.com/khsr25/hsr_java_app.git'
                }
            }
        }
    }
}