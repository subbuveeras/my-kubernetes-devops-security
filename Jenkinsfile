pipeline {
  agent any

  stages {
      stage('GIT Version') {
         \\   steps {
           \\   sh "mvn clean package -DskipTests=true"
             \\ archive 'target/*.jar' //myown comment
           \\ }
        steps{
          sh "git version"
        }
        }   
    }
}
