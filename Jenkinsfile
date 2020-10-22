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
               		sh'export PYTHONPATH=$WORKSPACE:$PYTHONPATH'
			
			
		}
                      
        }
        
        }
    }

