pipeline {
 tools { nodejs "nodejs" }
 agent any
 stages {
  stage('Getting Repo') {
 steps {
  git 'https://github.com/Sameerdhole/docker_project.git'
 }
 }
  stage('Build Web app') {
 steps {
  echo ' building web app'
 }
 }
  stage('Deploy Web App') {
 steps {
  echo ' deploying web app'
 }
 }
 }
}
