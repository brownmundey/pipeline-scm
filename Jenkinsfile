pipeline {
	agent {
		label {
			label "slave-1"
		}
	}
	stages {
		stage ("stage-1") {
			steps {
				sh "yum install tree -y"
			}
		}
	}
}
