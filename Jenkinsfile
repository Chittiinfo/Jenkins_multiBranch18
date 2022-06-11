node('built-in') 
{
    stage('ContinuousDownload_Loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('ContinuousBuild_Loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
#testing
