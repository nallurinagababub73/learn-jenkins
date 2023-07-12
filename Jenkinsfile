pipeline {
 agent { node { label 'workstation' } }
  stages{
   stage ('compile') {
    steps {
       sh 'echo hello'
       sh 'touch file1'
       }

     }
   }
   post {
    always {
     cleanWs()
    }
   }
}