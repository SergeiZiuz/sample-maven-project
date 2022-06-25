pipeline {
    agent any 
    stages {
        stage('maven install') {
            steps {
                withMaven(globalMavenSettingsConfig: 'null', jdk: 'null', maven: 'Maven', mavenSettingsConfig: 'null') {
                    sh 'mvn clean install'
                }
            }
        }
    }
}
