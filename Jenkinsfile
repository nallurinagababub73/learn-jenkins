pipeline {
 agent { node { label 'workstation' } }

 parameters { string(name: 'ENV', defaultValue: 'dev', description: 'Give environment name') }

 triggers {
         cron('H/1 * * * *5')
         }
   stages {
    stage ('compile') {
     steps {
      sh 'echo hello'
     }
    }
   }
}