pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building'
      }
    }

    stage('Test firefox') {
      parallel {
        stage('Test firefox') {
          steps {
            echo 'Firfox test'
          }
        }

        stage('Test Chrome') {
          steps {
            echo 'test chrome'
          }
        }

        stage('') {
          steps {
            echo 'test opera'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}