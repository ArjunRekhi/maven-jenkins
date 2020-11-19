pipeline{
        agent any
        stages{
            stage('build'){
              steps{
              sh 'mvn clean'
             }
            }
            
            stage('test'){
              steps{
              echo 'Test Stage'
             }
            }
            stage('deploy'){
              steps{
              sh 'mvn deploy'
             }
            }
        }
}
