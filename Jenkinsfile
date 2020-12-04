pipeline{
        agent any
        stages{
            stage('build'){
              steps{
              bat 'mvn -f C:/Users/ARJUN/.jenkins/workspace/End-Sem/my-app install'
             }
            }
            
            stage('test'){
              steps{
              echo 'Test Stage'
             }
            }
            stage('deploy'){
              steps{
              bat 'mvn -f C:/Users/ARJUN/.jenkins/workspace/End-Sem/my-app deploy'
             }
            }
        }
}
