<<<<<<< HEAD
node('ec2slave')
{
agent any

stages
{
	stage('test')
	{  steps{sh 'echo "this node is working"'  }  }

}


}
=======
node()
{
 agent any

stages
{
        stage('clone')
        { checkout scm
    
        }

        stage('task')
        { steps { sh 'echo task completed'

        }
        }
}
}


>>>>>>> 3da2ee4ca80db8483d1e955660facc39a11657eb
