pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'this is the build job'
        sh 'npm install'
      }
    }

    stage('test') {
      steps {
        echo 'this is the test job'
        sh 'npm test'
      }
    }

    stage('package') {
      steps {
        echo 'this is the package job'
        sh 'npm run package'
      }
    }

<<<<<<< HEAD
    stage('artifact') {
=======
    stage('Archieve') {
>>>>>>> 62fb7a67542a7e5f87f0eadb8c60ba84c4f3d8eb
      steps {
        archiveArtifacts '**/distribution/*.zip'
      }
    }

  }
  tools {
    nodejs 'nodejs'
  }
  post {
    always {
      echo 'this pipeline has completed...'
    }

  }
<<<<<<< HEAD
}
=======
}
>>>>>>> 62fb7a67542a7e5f87f0eadb8c60ba84c4f3d8eb
