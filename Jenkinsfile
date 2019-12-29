pipeline{
agent any{
stages{
stage('Compile Stage'){
steps{
withMaven(Maven : 'C:\apache-maven-3.6.2')
{
cd 'mvn clean compile'
}
}
}
}
}
}
