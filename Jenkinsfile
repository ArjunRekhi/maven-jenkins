pipeline{
        agent any
        stages{
            stage('clean'){
              steps{
              sh 'sudo mvn -f my-app clean'
             }
            }
            
            stage('install'){
              steps{
              sh 'sudo mvn -f my-app install'
             }
            }
        }
}
