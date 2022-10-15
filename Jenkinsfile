#!/usr/bin/env groovy
stage 'build_Project'
node{
  if(isUnix()){
  sh 'gradle build --info'

  }
  else{
    bat 'gradle build --info'
  }
}
