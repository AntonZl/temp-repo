pipeline {
    agent any
    stages {
        stage('Stage1'){
           steps {
               sh '''
               ls -la
//                if sort -C numbers; then
//                   # return code 0
//                   echo "sorted"
//                 else
//                   # return code not 0
//                   echo "not sorted"
//                 fi
                sort -C file || echo -n "not " ; echo "sorted"
               '''
           }
        }
    }
}
