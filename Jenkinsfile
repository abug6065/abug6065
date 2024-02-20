pipeline{
  agent any
  stages{
    stage(git clone){
      steps{
        sh 'git branch: 'main', credentialsId: 'github', url: 'https://github.com/abug6065/abug6065.git''
      }
    }
  }
}
