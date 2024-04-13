pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat '"C:\\Users\\User\\AppData\\Local\\Programs\\Python\\Python311\\python.exe" --version'
      }
    }
    stage('main') {
      steps {
        bat '"C:\\Users\\User\\AppData\\Local\\Programs\\Python\\Python311\\python.exe" main.py'
      }
    }
  }
}
