pipeline {
  options {
    buildDiscarder(logRotator(numToKeepStr: "5"))
    disableConcurrentBuilds()
    skipDefaultCheckout()
    timestamps()
  }
  agent {
    label "prod"
  }
  stages {
    stage("Empty") {
      steps {
      }
    }
  }
}