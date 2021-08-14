pipeline{
        agent any
        stages{
            stage('clean'){
              steps{
              sh 'sudo mvn clean'
             }
            }
            
            stage('install'){
              steps{
              sh 'sudo mvn install'
             }
            }
        }
}
