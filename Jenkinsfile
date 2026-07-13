pipeline {
  agent any

  tools {
	terraform 'terraform-1.15.8'
  }

  stages {
	stage('Hello World') {
	  steps {
		sh 'terraform version'
		sh 'terraform init'
	  }
	}
  }
}
