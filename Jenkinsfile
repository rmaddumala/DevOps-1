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
                    pwd
                    sh /var/lib/jenkins/workspace/Pipeline_From_Git/shell1.sh
                    
                   
                '''
            }
        }
    }
}
