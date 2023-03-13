pipeline {
  agent {
     label 'ansible'
     }
  stages {
    stage('hello') {
      steps{
 echo 'hello world'
    }
   }
  }
}


@library('roboshop') _

pipeline {
 agent any
 stages {
 stage('test') {
 steps {
 script {
 test
 }
 }
 }
 }
 }