pipeline {
  agent any
  stages {
    stage('') {
      steps {
        parallel(
          "Step 1": {
            sleep 10
            
          },
          "Step 2": {
            echo 'Testing'
            
          },
          "Step 3": {
            mail(subject: 'Test Message', body: 'Test Message', from: 'jjuvingo@go-vsg.com', to: 'jjuvingo@go-vsg.com')
            
          }
        )
      }
    }
    stage('Phase 1') {
      steps {
        figlet 'This is a test'
      }
    }
  }
}