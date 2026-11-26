pipeline {

    agent any

    stages {

        stage('Preparacion') {
            steps {
                echo 'Iniciando nuestro Pipeline'
                echo 'Preparando el proyecto'
            }
        }

        stage('Build') {
            steps {
                echo 'Construyendo nuestra aplicacion'
            }
        }

        stage('Test') {
            steps {
                echo 'Ejecutando pruebas'
                sh 'sh hello.sh'
                sh 'exit 1'
            }
        }

        stage('Finalizacion') {
            steps {
                echo 'Pipeline terminado correctamente'
            }
        }

    }

}
