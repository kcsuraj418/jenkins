#!/bin/sh
pipeline{
agent any
  stages{
    stage("build"){
      steps{
        python /var/lib/jenkins/workspace/test_suraj/hello.py
      }
    }
    stage("test"){
      steps{
        echo "tested successfully"
      }
    }
  }
}
