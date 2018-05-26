pipeline {
  agent any
  stages{
        stage('Build'){
            steps{
	            echo 'Build'
	        }
        }

        post {
            always{
                echo 'Esto siempre saldra por pantalla'
            }
        }


        stage('Test'){
            steps{
                echo' hola desde fase2'
	        }
        }

        }
}

	
