pipeline {
    agent any

    parameters {
        booleanParam(defaultValue: true, description: '', name: 'userFlag')
    }

    stages {
        stage("foo") {
            steps { 
                echo 'ddddddddddddddddddddddddd'
                  echo "flag: ${params.userFlag}"
            }  
        }
    }
}