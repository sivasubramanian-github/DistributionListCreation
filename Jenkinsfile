pipeline {
  agent any
  stages {
    stage('CheckDLexist') {
      parallel {
        stage('CheckDLexist') {
          steps {
            echo 'check the dL is alrady exist or not'
            sleep 5
            echo 'the DL is exist '
          }
        }

        stage('checkuserexist') {
          steps {
            echo 'check user exist'
            sleep 5
            echo 'end'
          }
        }

      }
    }

    stage('createDL') {
      steps {
        echo 'Going to creatre new DL'
        echo 'Dl succesully created'
      }
    }

  }
}