pipeline {
	agent {
		label {
			label "built-in"
			customWorkspace "/var/www/html"
		}
	}
	stages {
		stage ("stage-1") {
			steps {
				sh "cd/var/www"
				sh "chmod -R 777 html"
			}
		}
		stage ("permission") {
			steps {
				sh "chmod 777 /var/www/html/index.html"
			}
		}
		
		
	}
}
