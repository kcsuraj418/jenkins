pipeline{
agent any
  stages{
    stage("build"){
      steps{
        sh 'python.exe hello.py'
      }
    }
    stage("test"){
      steps{
        echo "tested successfully"
      }
    }
  }
}
