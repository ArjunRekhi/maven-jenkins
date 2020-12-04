pipeline{
        agent any
        stages{
            stage('build'){
              steps{
              bat 'mvn -f C:/Users/ARJUN/.jenkins/workspace/End-Sem/my-app clean'
             }
            }
            
            stage('test'){
              steps{
              bat 'mvn -f C:/Users/ARJUN/.jenkins/workspace/End-Sem/my-app test'
             }
            }
            stage('deploy'){
              steps{
              bat 'mvn -f C:/Users/ARJUN/.jenkins/workspace/End-Sem/my-app install'
             }
            }
        }
}
