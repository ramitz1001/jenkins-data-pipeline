pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    bat 'pip install pandas' // Installer les dépendances
                    bat 'python data_analysis.py' // Exécuter le script Python
                }
            }
        }
    }
}
