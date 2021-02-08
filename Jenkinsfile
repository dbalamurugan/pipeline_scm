pipeline {
    agent any

    parameters {
        booleanParam(defaultValue: true, description: '', name: 'userFlag')
        string(name : 'build_version',defaultValue :'1234',description:'enter build value')
              choice(choices: ['yes', 'no'], description: 'yes/mp', name: 'reg')
    }

    stages {
        stage("foo") {
            steps { 
                echo 'ddddddddddddddddddddddddd'
                  echo "flag: ${params.userFlag}"
                  echo "string input values is ${build_version}"
                  echo "choice value is  ${params.reg}" 
                  n = ${params.reg}
                for (index in 1 .. 5) {
                    
                        echo "looping"
                }

            }  
        }
    }
}