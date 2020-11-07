pipeline{
	agent any
	stages{
		stage("Bring Grid up"){
			steps{
				sh "docker-compose up --no-color"
			}
		}
		stage("Bring Grid Down"){
			steps{
				sh "docker-compose down"
			}
		}
	}
}