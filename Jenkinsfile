pipeline {
agent any
stages{
  stage('Build'){
    steps{
      sh '/usr/share/maven/bin/mvn clean install'
    }
  }
}
stages{
  stage('Test'){
    steps{
      sh '/usr/share/maven/bin/mvn clean test'
    }
  }
}
}
