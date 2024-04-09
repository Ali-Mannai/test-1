pipeline {
  agent any
      triggers {
        // Déclencheur pour écouter les webhooks de GitHub
        githubWebhook()
    }
  
  stages {
    stage('build') {
      steps {
        echo 'build completed.....'
      }
    }

  }
}
