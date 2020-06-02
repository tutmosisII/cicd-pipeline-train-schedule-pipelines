pipeline {
    agent any
    stages {
        stage ("Build"){
            steps {
                echo "Corriendo Paso 1 de Build"
                sh './gradlew build --no-daemon'
                archiveArtifacs artifacs: 'dist/trainSchedule.zip'
            }
        }
    }
}