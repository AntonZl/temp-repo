pipeline {
    agent any
    stages {
        stage('Stage1'){
           steps {
               sh '''
               ls -la

                sort -C numbers || echo -n "not " ; echo "sorted"
               '''
           }
        }
    }
}
