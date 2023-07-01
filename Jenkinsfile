node('built-in') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/Michoaddy/jenkins_multibranch.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
