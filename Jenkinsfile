pipeline {
 agent { node { label 'workstation' } }
  stages{
   stage ('compile') {
    steps {
       sh 'echo hello'
       sh 'mkdir hemasri'
       }

     }
   }
   post {
    always {
     cleanWs()
    }
   }
}