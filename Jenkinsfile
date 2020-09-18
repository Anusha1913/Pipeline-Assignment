pipeline{
  agent none
  stages {
    stage ('C') {
      agent {label 'C'}
      steps {
        git 'https://github.com/Anusha1913/c_programs.git'
        sh 'make'
        
      }
    }
    stage ('JAVA') {
      agent {label 'Java'}
      steps{
        
        git 'https://github.com/Anusha1913/JAVA1.git'
        sh 'mvn clean install'
        
      }
    }
  }
}
