node('master') 
{
    stage('Continuous Download_master') 
    {
        git 'https://github.com/sunildevops77/maven.git'
    }
    stage('Continuous Build_master') 
    {
        sh '/opt/maven/bin/mvn package'
    }
}
