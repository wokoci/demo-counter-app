pipeline{
    agent any
    stages{
        stage{
            stage('Git Checkout'){
                step{
                    git branch: 'main', url: 'https://github.com/wokoci/demo-counter-app.git'
                }

            }
        }
    }
}