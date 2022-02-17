pipeline {
    agent any

    stages {
        stage('Crear archivo') {
            steps {
                echo 'Estoy creando un archivo'
                sh 'touch archivo.txt'
            }
        }
        stage('Ingresando datos archivo') {
            steps {
                echo 'Ingresando datos archivo'
                sh 'echo hola > archivo.txt'
            }
        }
        stage('Enlisto los archivos') {
            steps {
                sh 'ls'
            }
        }
    }
}
