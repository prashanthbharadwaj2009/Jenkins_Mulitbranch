node('built-in') 
{
    stage('Continous Download_Master') 
	{
		git 'https://github.com/prashanthbharadwaj2009/maven.git'
	}
	stage('Continous Build') 
	{
		sh 'mvn package'
	}
}
