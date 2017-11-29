pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'ls -l'
                dir ('foo') {
                 writeFile file:'dummy', text:''
                 }
                }
               }
                stage('Test') {
                 steps {
                  sh 'ls -l'
                  }
                 }
                 stage('Deploy') {
                  steps {
                       echo 'Hello World'
                       }
                      }
                     }
                    }
