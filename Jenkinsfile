#!/usr/bin/env groovy

node {
    stage('checkout') {
        checkout scmGit(branches: [[name: 'main'], [name: 'feature/test']], extensions: [], userRemoteConfigs: [[url: 'git@github.com:Daviddager/gradle-test-pipeline.git']])
       sh 'env | sort'
    }
}
