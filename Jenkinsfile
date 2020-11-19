pipeline{
        agent any
        stages{
            stage('build'){
              steps{
              bash 'mvn clean'
             }
            }
            
            stage('test'){
              steps{
              echo 'Test Stage'
             }
            }
            stage('deploy'){
              steps{
              bash 'mvn deploy'
             }
            }
        }
}
