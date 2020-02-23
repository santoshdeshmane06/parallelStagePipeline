pipeline
{
	agent any
	stages
	{
		stage
		parallel{
		
		stage('print hi')
		{
			steps
			{
				sh 'echo hi in linux'
			}
		}
		stage('print hi')
		{
			steps
			{
				sh 'echo hi in windows'
			}
		}
	}
}
