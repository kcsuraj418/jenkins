#!/bin/sh
pipeline{
agent any
  stages{
    stage("build"){
      steps{
        sh 'python hello.py'
      }
    }
    stage("test"){
      steps{
        echo "tested successfully"
      }
    }
  }
}
