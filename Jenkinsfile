pipeline {
    agent any
    stages {
        stage('Check') {
                steps {
                        echo 'Hi, this is Arslan'
			
                }
        }
	    stage('Build'){
		    
		steps {
			sh'rm -rf test'
			sh 'git clone https://github.com/Arslan160572/test.git'
        }
	    }
        stage('Run') {
		steps {
			sh'pip3 install flask'
               		sh'export PYTHONPATH=$WORKSPACE:$PYTHONPATH'
			sh'nohup python3 pyflask.py'
			
		}
                      
        }
        
        }
    }

