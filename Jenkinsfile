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
				sh 'which docker'
				sh 'docker version'
			}
		}
	}
}
