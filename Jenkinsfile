pipeline {
 agent { node { label 'workstation' } }
 options {
   ansiColor('xterm')
 }
         stages {
          stage ('compile') {
            steps {
               sh 'echo hello'
            }
          }
        }
   post {
    always {
     cleanWs()
    }
   }
}