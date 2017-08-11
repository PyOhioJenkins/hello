pipeline
{
	agent any
	
	tools
	{
		docker 'Docker'
	}
	
	stages
	{
		stage('Greeting')
		{
			steps
			{
				echo 'Hello PyOhio!'
				sh 'docker version'
			}
		}
	}
}
