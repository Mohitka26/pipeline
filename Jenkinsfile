pipeline {
			agent any 
			stages {
				  stage('Build') {
					           steps {
                                          		sh 'sleep 15; echo "This is a Build stage"'			
					                 }
				                 }

				  stage('Test'){
				 	          steps {
					
                                                 sh '''
							sleep 15
							echo "This is a Test stage"
                                    		    '''
					                }
				               }

				  stage('Deploy'){
					          steps {
               					        sh 'sleep 15; echo "This is a Build stage"'
 
					                }
				                 }

				  stage('My-stage'){
					          steps {
					
					                }
				                   }	
			        }
		}
