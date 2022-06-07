pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        bat(script: 'mvn -B -DskipTests clean package', encoding: 'utf-8', label: 'dd')
      }
    }

  }
}