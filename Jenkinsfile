pipeline {
    agent any
    stages {
        stage('One') {
                steps {
                        echo 'Hi, this is Zulaikha from edureka'
			
                }
        }
	    stage('Two'){
		    
		steps {
			sh'rm -rf test'
			sh 'git clone https://github.com/Arslan160572/test.git'
        }
	    }
        stage('Three') {
		steps {
               		sh'export PYTHONPATH=$WORKSPACE:$PYTHONPATH'
			sh'python3 pyflask.py'
		}
                      
        }
        
        }
    }

