pipeline{
        agent any
        stages{
            stage('build'){
              steps{
              bat 'mvn install'
             }
            }
            
            stage('test'){
              steps{
              echo 'Test Stage'
             }
            }
            stage('deploy'){
              steps{
              bat 'mvn deploy'
             }
            }
        }
}
