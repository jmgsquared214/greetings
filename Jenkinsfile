#!groovy

// simple Jenkinsfile to pull source and build

node {
       def gradleLoc = tool 'gradle32'
       stage('source') {
          checkout scm
       }
       stage('build') {
          sh "'${gradleLoc}/bin/gradle' build"
       }
         
}
   
