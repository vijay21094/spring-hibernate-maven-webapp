node{
stage('SCM checkout')
{ 
git'https://github.com/vijay21094/spring-hibernate-maven-webapp'
}
stage('Compile-package')
{
  def mvnHome = tool name: 'maven3', type: 'maven'
  bat " ${mvnHome}/bin/mvn package "
}
}
