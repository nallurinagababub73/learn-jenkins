pipeline {
 agent { node { label 'workstation' } }

 parameters { string(name: 'ENV', defaultValue: 'dev', description: 'Give environment name') }
   stages {
    stage ('compile') {
     steps {
      sh 'echo hello'
     }
    }
   }
}