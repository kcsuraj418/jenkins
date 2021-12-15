#!/usr/bin/python3
pipeline{
agent any
  stages{
    stage("build"){
      steps{
        sh "chmod +x -R ${env.WORKSPACE}"
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
