pipeline{
agent { docker { image 'python:3.10.1-alpine' } }
  stages{
    stage("build"){
      steps{
        sh 'hello.py'
      }
    }
    stage("test"){
      steps{
        echo "tested successfully"
      }
    }
  }
}
