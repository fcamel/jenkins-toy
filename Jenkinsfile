pipeline {
	agent any 

	stages {
		stage('Checkout') {
			steps {
				checkout scm
			}
		}

		stage('Run Script') {
			steps {
				sh '''#!/bin/bash
				python3 hello.py
				'''
			}
		}
	}
}
