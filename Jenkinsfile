node{
stage('scm checkout'){
 
git 'https://github.com/sangameshwar2804/CRM_Maven_Jenkins'
}
stage('compile package'){
   def mvnHome= tool name: 'maven-3', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
}
}
