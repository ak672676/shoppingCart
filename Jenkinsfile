

pipeline{


agent any 
triggers {
    cron('* * * * *')
  }
  
stages {
  stage('Build') {
    steps {
      bat 'echo "This is my first step"'
    }
  }
  stage('Test') {
    steps{
      bat 'echo "This is my Test step"'
    }
  }
  stage('Deploy') {
    steps {
      bat 'echo "This is my Deploy step"'
    }
  }
}
}
