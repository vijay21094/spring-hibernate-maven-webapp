node{
stage('SCM checkout')
{ 
git'https://github.com/vijay21094/spring-hibernate-maven-webapp'
}
stage('clean')
{
  def mHome = tool name: 'maven2', type: 'maven'
  bat " ${mHome}/bin/mvn clean "
}
}
