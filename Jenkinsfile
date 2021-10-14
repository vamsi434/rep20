node('master') 
{
    stage('Continuous master_Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous master_Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
