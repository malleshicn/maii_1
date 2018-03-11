pipeline {
  agent {
    node {
      label 'jenkins'
    }
    
  }
  stages {
    stage('test1') {
      steps {
        sh '''#!/bin/bash
echo "Hello World"'''
      }
    }
  }
}