pipeline{
        agent any
        stages{
            stage('clean'){
              steps{
              bat 'mvn -f C:/Users/ARJUN/.jenkins/workspace/End-Sem/my-app clean'
             }
            }
            
            stage('test'){
              steps{
              bat 'mvn -f C:/Users/ARJUN/.jenkins/workspace/End-Sem/my-app test'
             }
            }
            stage('install'){
              steps{
              bat 'mvn -f C:/Users/ARJUN/.jenkins/workspace/End-Sem/my-app install'
             }
            }
        }
}
