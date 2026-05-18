pipeline {
    agent any
    stages {
        stage('Preparar ingredientes') {
            steps {
                echo 'Comprando harina y huevos...'
            }
        }
        stage('Hornear a 200 grados') {
            steps {
                echo 'Metemos el pastel al horno...'
                sleep 3  // Le decimos a Jenkins que espere 3 segundos
            }
        }
        stage('Servir') {
            steps {
                echo '¡Pastel listo para comer!'
            }
        }
    }
}
