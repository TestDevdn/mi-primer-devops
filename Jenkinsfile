pipeline {
    agent any

    stages {
        stage('Clonar repo') {
            steps {
                git branch: 'main', url: 'https://github.com/TestDevdn/mi-primer-devops'
            }
        }

        stage('Compilar') {
            steps {
                echo 'Compilando...'
            }
        }

        stage('Pruebas') {
            steps {
                echo 'Ejecutando pruebas...'
            }
        }

        stage('Despliegue') {
            steps {
                echo 'Desplegando aplicación...'
            }
        }
    }
}

