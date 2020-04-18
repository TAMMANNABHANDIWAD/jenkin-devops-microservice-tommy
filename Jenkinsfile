// node {
// 	// stage('Build') {
// 	// 	echo "Build"
// 	// }
// 	// stage('Test') {
// 	// 	echo "Test"
// 	// }
// 	// stage('TIntegration_Test') {
// 	// 	echo "Integration Test"
// 	// }
// 	echo "Build"
// 	echo "Test"
// 	echo "Integration Test"
// }

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
	}
}
