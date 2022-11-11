pipeline {
	agent any
	stages {
		stage ("Inicio") {
			steps {
				sh 'mvn clean package -DskipTests=True'
			}
		}
	}
}
