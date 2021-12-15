pipeline{
agent any
  stages{
    stage("build"){
      steps{
        python 3 /var/lib/jenkins/workspace/test_suraj/hello.py
      }
    }
    stage("test"){
      steps{
        echo "tested successfully"
      }
    }
  }
}
