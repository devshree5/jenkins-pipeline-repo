pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                echo 'compiling source code ....this is compile phase testing'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing source code .... This is test phase'
            }
        }
        stage('package') {
            steps {
                echo 'creating package....  This is package  phase'
            }
        }
	stage('Deploy') {
		steps {
			echo 'deploying package ......This is the deploy  phase....'
		}
	}
    }
}
