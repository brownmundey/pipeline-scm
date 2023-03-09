pipeline {
	agent {
		label {
			label "slave-2"
		}
	}
	stages {
		stage ("stage-1") {
			steps {
				sh "sudo yum install tree -y"
				sh "sudo yum install httpd -y"
				sh "sudo service httpd start"
			}
		}
	}
}
