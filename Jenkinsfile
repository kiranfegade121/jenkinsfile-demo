pipeline {

     agent {
         label "linux-instance"
     }

     stages {

         stage("Build") {
             steps {
                 echo "Buiding a project"
             }
         }

         stage("Test") {
             steps {
                 echo "Testing an application."
             }
         }

         stage("Deploy") {
             steps {
                 echo "Deploying an application."
             }
         }
     }
}