pipeline {
    agent any
    stages {
        stage('Prueba Despliegue ---  kiloalo') {
            steps {
                timeout(time: 1, unit: 'MINUTES') {
                    sh 'for n in `seq 1 10`; do echo $n; sleep 1; done'
                }
                timeout(time: 1, unit: 'MINUTES') {
                    sh 'for n in `seq 1 15`; do echo $n; sleep 1; done'
                }
            }
        }
    }
}

