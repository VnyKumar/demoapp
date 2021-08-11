pipeline {
  agent none

  environment {
    IMAGE = "liatrio/petclinic-tomcat"
  }

  stages {

    stage('Build') {
       steps {
        //configFileProvider([configFile(fileId: 'nexus', variable: 'MAVEN_SETTINGS')]) {
          //sh 'mvn -s $MAVEN_SETTINGS clean deploy -DskipTests=true -B'
         sh 'echo "Hellow orld from jenkins file"'
          
        }
      }
    }
