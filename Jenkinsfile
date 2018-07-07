pipeline {
	agent any
	stages{
		stage('Build'){
			steps{
				sh 'groovy LinksPrinter.groovy'
			}
		}
		stage('Test'){
			steps{
				sh 'echo http://google.com'
			}
		}
		stage('Scan'){
			steps{
				sh 'echo http://yahoo.com'
			}
		}
	}
}