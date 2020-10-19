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
			git clone https://github.com/Arslan160572/test.git
        }
	    }
        stage('Three') {
               		sh'python3 pyflask.py'
			echo "Hello"
                      
        }
        
        }
    }

