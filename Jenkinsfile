#!/bin/sh
pipeline{
agent any
  stages{
    stage("build"){
      steps{
        sh "chmod +x -R ${env.WORKSPACE}"
        sh "python3 /var/lib/jenkins/workspace/test_suraj/hello_world.py"
      }
    }
    stage("test"){
      steps{
        echo "tested successfully"
      }
    }
  }
}
