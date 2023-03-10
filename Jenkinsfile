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
				sh "rm -rf *"
				sh "cd/var/www"
				sh "chmod -R 777 html"
			}
		}
		
	}
}
