pipeline {
  agent any
  stages {
    stage('Release Version Selection') {
      steps {
        input message: 'What is the version of the new release?', parameters: [string(defaultValue: '', description: '', name: 'release_version', trim: true)], submitter: 'avh,chw,rju,thomas.duellmann'   
        echo "Selected Version: $release_version"
      }
    }
  }
}  
