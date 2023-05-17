pipeline {
  agent any
    stages {
    stage ('step-1 Initialize') {
      steps {
        sh 'echo "Initializing..."'
      }
    }
    stage ('step-2 Cloning Git Repository') {
      steps {
        git branch: 'main', credentialsId: 'git_full', url: 'https://github.com/mdnishadnk/React-ToDoList.git'
        sh 'ls'
      }
    }
    stage ('step-3 Check Dockerfile') {
      steps {
        sh 'echo "Searching for Dockerfile..."'
      }
    }
    stage ('setpe-4 conditional operation') {
		steps {
			sh '''if [ -f Dockerfile ]; then
				echo "The Dockerfile exists."
			else
				echo "The Dockerfile does not exist."
			fi'''
			sh 'cat Dockerfile'
			}
		}
	}
	
}
