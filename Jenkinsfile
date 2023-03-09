pipeline {
	agent {
		label {
			label "slave-1"
		}
	}
	stages {
		stage ("stage-1") {
			steps {
				sh "sudo yum install httpd -y"
				sh "sudo service httpd start"
			}
		}
	}
}
