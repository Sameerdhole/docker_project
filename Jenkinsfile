pipeline {
 tools { nodejs "nodejs" }
 agent any
 stages {
  stage('Deploy Web App') {
 steps {
 sh 'cd webapp'
  sh ' npm install '
  sh 'npm start'
 }
 }
 }
}
