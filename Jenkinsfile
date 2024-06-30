pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Remplacez 'C:\\path\\to\\python.exe' par le chemin absolu vers votre exécutable Python
                    bat 'C:\Users\chris\AppData\Local\Programs\Python\Python310\python.exe -m pip install pandas' // Installer les dépendances
                    bat 'C:\Users\chris\AppData\Local\Programs\Python\Python310\python.exe  data_analysis.py' // Exécuter le script Python
                }
            }
        }
    }
}
