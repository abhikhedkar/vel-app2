pipeline {

	agent {
	
			label {
			
					label "built-in"
					customWorkspace "/mnt/vel-app2"
			}
	}
	
	stages {
	
		stage ('stage-1') {
		
			steps {
			
					sh "mkdir test"
			}
		
		}
	
		stage ('stage-2') {
		
			steps {
			
					sh "mkdir test-2"
			}
			
		}
	}

}
