pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'

                sh '''
                    pwd
                    whoami
                    ls -ltrah
                '''

            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {

                echo 'Deploying....'
            }
        }
    }
}

                echo 'Deploying.....'
                sh '''
                    echo "HELLO WORLD"
                    sh new_script.sh
                '''
            }
        }
    }
}

