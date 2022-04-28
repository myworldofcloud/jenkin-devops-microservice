pipeline {
	// agent any
	agent { docker {image "maven"}}
	stages {
		stage("Build") {
			steps {
				echo "Build"
				
			} }
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