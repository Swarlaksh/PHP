pipeline {
    agent any
 
    stages {
        // stage('build') {
        //     steps {
        //         sh ''' whoami
        //         docker build -t dockerdndocker .'''
        //     }
        // }
        stage('run') {
            steps {
                sh ''' 
                pip install --user --extra-index-url https://test.pypi.org/simple/ boman-cli-uat==0.7 '
                ~/.local/bin/boman-cli-uat -a run'''
            }
        }
    }
}
