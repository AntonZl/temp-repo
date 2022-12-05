pipeline {
    agent any
    stages {
        stage('Stage1'){
           steps {
               sh '''
               sort -C file || echo -n "not " ; echo "sorted"
               '''
           }
        }
    }
}
