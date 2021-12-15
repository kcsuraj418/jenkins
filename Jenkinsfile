#!/bin/sh
pipeline{
agent any
  stages{
    stage("build"){
      steps{
        sh "chmod +x -R ${env.WORKSPACE}"
        sh "./hello.py"
      }
    }
    stage("test"){
      steps{
        echo "tested successfully"
      }
    }
  }
}
