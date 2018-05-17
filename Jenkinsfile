pipeline{
	agent none
	stages {
	   	stage('Preparation') { // for display purposes
			steps {
        			echo "Preparation"
			        git 'https://github.com/jianzzz/jenkins-test.git' 
			}
   	   	}
   		stage('Build') {
			steps{
			        echo "build"
			}
   		}
		stage('Results') {
			steps{
			        echo "Results"
			}
   		}
	}
}
