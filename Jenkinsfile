node('built-in') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/samhirdevops/project1-.git'
	}
	stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
	}
}
