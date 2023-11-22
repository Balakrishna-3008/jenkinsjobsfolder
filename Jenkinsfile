pipeline {
	agent any
	stages {
		stage('System Details 1st Stage') {
			steps {
				script {
					sh 'uname -a'
						}
					}
			}
 
		stage('Memory Details 2nd Stage') {
			steps {
				script {
					sh 'free -m'
						}
					}
				}
 
		stage('CPU Details 3rd Stage') {
			steps {
				script {
					sh 'lscpu'
						}
					}
				}
 
		stage('Today\'s Date 4th Stage') {
			steps {
				script {
					sh 'date'
						}
					}
				}
 
		stage('uptime 5th Stage') {
			steps {
				script {
					sh 'uptime'
					}
				}
			}
 
		stage('current User 6th Stage') {
			steps {
				script {
				 sh 'whoami'
				 }
			}
		}
 
		stage('Timing According to India +5:30UTC 7th Stage') {
			steps {
				script {
					sh 'TZ="Asia/Kolkata" date'
					}
				}
			}
		}	
	}
