pipeline{
  agent any
  stages {
      stage('build'){
        steps{
              echo 'building...'
            }
        }
        stage('test'){
            steps{
                sh 'Python --version
              }
        }
        stage('Deploy'){
            steps{
                echo'Deploying...'
              }
        }
    }
}
