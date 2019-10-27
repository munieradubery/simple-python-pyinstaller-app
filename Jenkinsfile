pipline{
    agent none

    stages {
        stage('Build') {
            agent {
                docker {
                    image 'python:2-apline'
                }
            }

            steps {
                sh 'python -m py_compile sources/add2vals.py sources/calc.py'
            }
        }
    }
}
    
