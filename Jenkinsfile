pipeline {
    agent {
        label 'agent-1'
    }
    stages {
        stage('validar hello world') {
            steps {
                sh 'echo Hello world: $(hostname)'
            }
        }

        stage('segundo step') {
            steps {
                sh 'echo Hello world2: $(date)'
            }
        }

        stage('tercer step') {
            steps {
                sh 'echo Hello world3: $(date)'
            }
        }
    }
}