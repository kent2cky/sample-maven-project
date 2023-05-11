pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
            withMaven(globalMavenSettingsConfig: '', jdk: '', maven: '', mavenSettingsConfig: '', traceability: true) {
                // some block
                sh 'mvn clean install'
            }       
        }
    }

  }
}
