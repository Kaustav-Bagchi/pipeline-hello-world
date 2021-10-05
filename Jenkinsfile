Repipeline{
	agent any
	stages{
		stage("Pre-Checks")
		{
			steps
			{
				sh 'ls -al'
				sh 'mvn --version'
			}
		}
		stage("Build")
		{
			steps
			{
				sh 'mvn clean install'	
			}
		}
	}
}
