
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World!!!s'
                script{
                    if(isUnix()){
                           print "Unix"
                    }else{
                        print "Not Unixs"
                    }
                }
            }
        }
    }
}
