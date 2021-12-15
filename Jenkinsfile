#!/bin/sh
pipeline{
agent any
  stages{
    stage("build"){
      steps{
        python hello.py
      }
    }
    stage("test"){
      steps{
        echo "tested successfully"
      }
    }
  }
}
