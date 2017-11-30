node('aws_slave')
{
 agent any

stages
{
        stage('check')
        { steps{ sh 'hostname'
                 sh 'echo "this is the slave node"'     }
        }

        stage('task')
        { steps { sh 'sudo yum install -y git'

        }
        }
}
}


