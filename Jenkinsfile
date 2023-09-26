pipeline{

    agent any

    stages{
         
        stage('Git Checkout'){
            steps{
            script{
                git branch: "main",  url: "https://github.com/boypansit/boydevops_java_app.git"
            }
        }
        }      
    }
}