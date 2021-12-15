#!/bin/sh
pipeline{
agent any
  stages{
    stage("build"){
      steps{
        python3 /var/lib/jenkins/workspace/test_suraj/hello.py
      }
    }
    stage("test"){
      steps{
        echo "tested successfully"
      }
    }
  }
}
