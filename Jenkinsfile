pipeline
{
	agent any
	
	stages
	{
		stage('Greeting')
		{
			steps
			{
				echo 'Hello PyOhio!'
				sh 'echo $PATH'
				sh '/usr/local/bin/docker version'
			}
		}
	}
}
