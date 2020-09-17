// Pipeline para proyectos Android
//
// V.1.0.0
//

def server_up = false

pipeline {
agent any
   // agent { label "sdk5" }
    stages {
        stage('Tag') {
            steps {
		bat "git tag"
		 bat "La ultima tag es:"
		   bat" git tag describe"
            }
        }
	
    }
}  
