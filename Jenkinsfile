pipeline{
  agent any
  stages{
    stage('main'){
      steps{
           sh 'mvn clean package'
      }
  }
    stage('test'){
      steps{
        sh 'mvn clean test'
      }
    }
}
}
