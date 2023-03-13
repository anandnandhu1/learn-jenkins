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


@library('roboshop')

pipeline {
 agent any
 stages {
 stage('test') {
 steps{
 script{
 def abc="hello"
 def xyz =10

 print "abc = ${abc}"
 print "xyz = ${xyz}"

 print abc

 }
 }
 }
 }
}