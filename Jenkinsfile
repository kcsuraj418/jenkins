#!/bin/sh
#!/usr/bin/python3
pipeline{
agent any
  stages{
    stage("build"){
      steps{
        sh "chmod +x -R ${env.WORKSPACE}"
        sh "python3 hello_world.py"
      }
    }
    stage("test"){
      steps{
        echo "tested successfully"
      }
    }
  }
}
