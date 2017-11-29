pipeline {
  agent any
  stages {
    stage('Inicio') {
      parallel {
        stage('Inicio') {
          steps {
            sh '''touch itworks.txt
'''
            sleep 20
          }
        }
        stage('Cont') {
          steps {
            sh 'echo \'eqwqw\''
            sleep 10
          }
        }
      }
    }
    stage('Phase2') {
      steps {
        sh 'echo "add my jenkins home\'>> $JENKINS_HOME"'
        echo 'we are working on $WORKSPACE'
      }
    }
  }
}