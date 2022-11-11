pipeline {
	agent any
	stages {
		stage ("Inicio") {
			steps {
				sh '/opt/maven/bin/mvn clean package -DskipTests=True'
			}
		}
	}
}
