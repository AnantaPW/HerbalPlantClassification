pipeline{
	agent any
	stages{
		stage('Stage #1'){
			steps{
				set /p username = "Enter username : "
				echo "Hi %username% This is stage 1 "
			}
		}
		stage('Stage #2'){
			steps{
				echo "This is stage 2"
			}
		}
	}
}
