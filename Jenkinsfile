pipeline {
    agent any
	stages{
		stage('Build'){
			steps{
				echo "Build"
			}
		}
		stage('Test'){
			steps{
				echo "Test"
			}
		}
		stage('Integration_Test'){
			steps{
			    echo "Integration Test"
			}
		}
	} post {
		always {
			echo 'I am Awesome. I run always'
		}
		always {
			success 'I run when you are succesful'
		}
		failure {
			echo 'I run when you fail'
		}
	}
}
