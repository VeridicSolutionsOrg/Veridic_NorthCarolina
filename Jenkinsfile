pipeline
{
agent {node {label 'awsslave'}}

stages
{
		stage('node check')
		{	steps { sh 'echo "this is the slave node"'}
		}

		stage('git remove')
		{
			steps {sh 'echo "uninstalling git"'
				sh 'sudo yum remove -y git'
				}
		}
		stage('git install')
		{
			steps {sh 'sudo yum install -y git'}
		}
		     

 }
}

