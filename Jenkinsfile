node{
stage('SCM checkout')
{ 
git'https://github.com/vijay21094/spring-hibernate-maven-webapp'
}
stage('Compile-package')
{
  def M2_Home = tool name: 'maven3', type: 'maven'
  bat " ${M_Home}/bin/mvn package "
}
}
