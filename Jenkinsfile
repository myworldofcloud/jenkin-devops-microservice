pipeline {
	agent any
	//agent { docker {image "maven:3.6.3"}}
	stages {
		stage("Build") {
			steps {
				echo "Build"
				echo "$PATH"
				echo "BUILD_NUMBER - $env.BUILD_NUMBER"
				echo "$env.BUILD_ID"
				echo "$env.JOB_NAME"
				} 
				}


		stage("Test") {
			steps {
				echo "Test"
			} }
		stage("Integration Test") {
			steps {
				echo "Integration Test"
			}
		}
		
		} 
		
		post 
		 {  
			always {
			
		   echo "Iam awesomw"
		     }

			 success {
			
		   echo "Successful"
		     }
		   
		   failure {
			
		   echo "Failed"
		     }
		   }
}