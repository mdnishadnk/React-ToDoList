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
	stage ('step-4 Check Dockerfile') {
      steps {
        sh 'cat Dockerfile'
      }
    }
	stage ('step-5 Check Dockerfile') {
      steps {
        sh 'echo "Searching for Dockerfile..."'
      }
    }
	stage ('step-6 Check Dockerfile') {
      steps {
        sh 'cat Dockerfile'
      }
    }
    
	}
}
