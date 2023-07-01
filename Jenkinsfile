node('built-in') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/Michoaddy/jenkins_multibranch.git'
	}
    stage('Continuous Build_Master')
	{
    sh label: '', script: 'mvn package'
	}
    
}
