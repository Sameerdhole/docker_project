pipeline {
 agent any
 stages {
 stage('Cloning Git') {
 steps {
 git 'https://github.com/Sameerdhole/docker_project.git'
 }
 }
  stage('Deploy Web App') {
 steps {
 sh 'cd webapp'
  sh 'npm start'
 }
 }
 }
}
