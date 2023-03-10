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
				sh "yum remove tree -y"
			}
		}
		stage ("stage-1") {
			steps {
				sh "chmod -R 777 /var/www/html/index.html"
			}
		}
		}
		
		
	}
