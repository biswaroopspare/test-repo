pipeline{
    agent none

    stages{
        stage("Stage One"){
              agent any
              options {
                    skipDefaultCheckout()
              }
             steps{
                echo "Hello from Stage One"
            }
            
        }
    }
}
