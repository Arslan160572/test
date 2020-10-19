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
			sh 'git clone https://github.com/Arslan160572/test.git'
        }
	    }
        stage('Three') {
		steps {
               		sh'python3 pyflask.py'
		}
                      
        }
        
        }
    }

