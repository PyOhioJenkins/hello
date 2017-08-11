pipeline
{
	agent any
	
	tools
	{
		org.jenkinsci.plugins.docker.commons.tools.DockerTool 'Docker'
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
