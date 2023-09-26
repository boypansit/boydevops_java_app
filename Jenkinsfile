pipeline{

    agent any

    stages{
         
        stage('Git Checkout'){
            steps{
            gitCheckout(
                branch: "main",
                url: "https://github.com/boypansit/boydevops_java_app.git"
            )
            }
        }
        }      
    }