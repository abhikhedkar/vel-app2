pipeline {

	agent {
	
			label {
			
					label "built-in"
					customWorkspace "/mnt/vel-app2"
			}
	}
	
	stages {
	
		stage ('deploy') {
		
			steps {
					sh "yum install httpd -y"
					sh "service httpd start"
					sh "cp -r /mnt/index.html /var/www/html"
					sh "chmod -R 777 /var/www/html/index.html"
			}
		
		}
	
		stage ('stage-2') {
		
			steps {
			
					echo "Build successful"
			}
			
		}
	}

}
