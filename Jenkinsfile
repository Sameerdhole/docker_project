pipeline {
 tools { nodejs "nodejs" }
 agent any
 stages {
  stage('Deploy Web App') {
 steps {
  sh ' npm install '
  sh 'npm start'
 }
 }
 }
}
