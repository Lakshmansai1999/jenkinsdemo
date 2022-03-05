pipeline {
        agent {
                node {
                        label "devServer"
                 }
         }
         stages {
                 stage('checkout') {
                         checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Lakshmansai1999/jenkinsdemo.git']]]) 
                  }
                  stage('build') {
                          echo "hello"
                   }
          }
  }                                             
