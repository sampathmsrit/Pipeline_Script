pipeline{
	agent any
	stages{
		stage('Source'){
			steps{echo "Compiled successfully"
			git 'https://github.com/simplilearn-github/Pipeline_Script.git'}
				}
		stage('Build'){
			steps{echo "Qulaity successfully"
			bat label: '', script: 'Build.bat'}
				}
		stage('Quality'){
			steps{echo "Deploy successfully"
			bat label: '', script: 'Quality.bat'}
				}
		stage('Deploy'){
			steps{echo "Test successfully"
			bat label: '', script: 'Deploy.bat'}
				}
		stage('Unit'){
			steps{echo "Test successfully"
			bat label: '', script: 'Unit.bat'}
				}

		}
	}
