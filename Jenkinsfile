pipeline {
    //agent any
    agent any
    stages {
        stage('Prueba Despliegue - Ais ') {
            steps {
                timeout(time: 1, unit: 'MINUTES') {
                    sh 'for n in `seq 1 3`; do echo $n; sleep 1; done'
                }
                timeout(time: 1, unit: 'MINUTES') {
                    sh 'for n in `seq 1 5`; do echo $n; sleep 1; done'
                }
            }
        }
    }
}

