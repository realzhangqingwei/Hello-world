pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh 'echo "这是第一句测试"'
                sh 'echo "这是第二句测试"'
            }
        }
    }
}
