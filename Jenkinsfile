pipeline {
 agent { node { label 'workstation' } }

 parameters { string(name: 'ENV', defaultValue: 'dev', description: 'Give environment name') }


 }
   stages {
    stage ('compile') {
     input {
             message "Should we continue?"
             ok "Yes, we should."


             }
     steps {
      sh 'echo hello'
     }
    }
   }
}