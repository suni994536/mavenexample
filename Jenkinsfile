pipeline {
  agent any
  tools {
    maven 'M2_HOME'
  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }
  }
}
