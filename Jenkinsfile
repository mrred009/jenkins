pipeline {
    agent any

    stages {
        
        stage("Trigger Test Job") {
            steps {
               build job: "push-to-test"
               }  
          }


        stage("Trigger Prod Job") {
            steps {
               build job: "push-to-prod"
               }
         }
     }
}
