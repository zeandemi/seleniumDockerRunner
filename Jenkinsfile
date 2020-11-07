pipeline{
	agent any
	stages{
		stage("Bring Grid up"){
			steps{
				bat "docker-compose up"
			}
		}
		stage("Bring Grid Down"){
			steps{
				bat "docker-compose down"
			}
		}
	}
}