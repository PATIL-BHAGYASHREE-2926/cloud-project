pipeline {
  agent any
  stages {
    stage ('Checkout') { steps { checkout scm } }
    stage ('Build')    { steps { bat 'build.bat' } }
    stage ('Test')     { steps { bat 'test.bat' } }
    stage ('Package')  { steps { bat 'package.bat' } }
  }
}
