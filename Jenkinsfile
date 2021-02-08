pipeline {
    agent any

    parameters {
        booleanParam(defaultValue: true, description: '', name: 'userFlag')
        string(name:build_version,defaultValue :'1234',description:'enter build value')
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