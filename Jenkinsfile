// Scripted
// node {
// 	stage('Build') {
// 		echo "Build"
// 	}
// 	stage('Test') {
// 		echo "Test"
// 	}
// 	stage('Test 2') {
// 		echo "Test 2"
// 	}
// }

// Declarative
pipeline{
	agent any
	stages{
		stage('Build'){
			steps{
				echo('Build')
			}
		}
		stage('Test'){
			steps{
				echo('Test')
			}
		
	}
		stage('Integration Test'){
			steps{
				echo('Integration Test')
			}
		
	}
}
post{
	always{
		echo 'triggered always'
	}
	success{
		echo 'triggered when build is success'
	}
	failure{
		echo 'triggered always'
	
}}
}
