pipeline {
  agent any // This defines the execution environment (any in this case)

  stages {
    stage('Checkout Code') { // Defines a stage named "Checkout Code"
      steps {
        git branch: 'main', // Fetches code from the specified branch
          url: 'https://github.com/nayaksanjana14/devOpsAsgmt.git' // URL of the Git repository
      }
    }

    stage('Install Dependencies') { // Defines another stage named "Install Dependencies"
      steps {
        sh 'npm install' // Executs a simple batch script to simulate an installation step
   }
    }
    stage('Start project') { // Defines another stage named "Install Dependencies"
      steps {
        sh 'npm run start' // Executs a simple batch script to simulate an installation step
   }
    }
  }
}
