pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "My first pipeline"'
                sh '''
                    echo "By the way, I can do more stuff in here"
                    ls -lah
                    whoami
                    who am i
                    df -kh
                    sudo su -
                    sh /root/Scripts/shell1.sh
                   
                '''
            }
        }
    }
}
