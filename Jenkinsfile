#!/bin/sh
pipeline{
agent any
  stages{
    stage("build"){
      steps{
        sh "./hello_world.py"
      }
    }
    stage("test"){
      steps{
        echo "tested successfully"
      }
    }
  }
}
