pipeline {
  agent any 
  stages {
    stage ('CICD'){
      steps {
         sh 'pip install --user --extra-index-url https://test.pypi.org/simple/ boman-cli-uat==0.7 && ~/.local/bin/boman-cli-uat -a run',
         
      }
    }
  }
}
