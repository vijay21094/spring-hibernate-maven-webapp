node{
stage('SCM checkout')
{ 
git'https://github.com/vijay21094/spring-hibernate-maven-webapp'
}
stage('clean')
{
  def mvnHome = tool name: 'apache-maven-3.6.3', type: 'maven'
  bat " ${mvnHome}/bin/mvn clean "
}
}
