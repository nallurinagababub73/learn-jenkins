pipeline {
 agent { node { label 'workstation' } }

 parameters { string(name: 'ENV', defaultValue: 'dev', description: 'Give environment name') }

 triggers {
         pollSCM('H/2 * * * *')
 }
   stages {
    stage ('compile') {
     steps {
      sh 'echo hello'
     }
    }
   }
}