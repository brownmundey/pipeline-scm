pipeline {
	agent {
		label {
			label "slave-1"
		}
	}
	stages {
		stage ("stage-1") {
			steps {
				sh "sudo yum install tree -y"
			}
		}
	}
}
