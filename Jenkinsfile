pipeline {
    agent any
    tools {
            maven 'MavenTest'
        }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}