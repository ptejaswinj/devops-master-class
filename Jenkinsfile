pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Build'){
            steps{
                echo'Build App'
            }
        }
stage('Test') {
            steps {
                echo 'Test App'
            }
        }
        stage('Deploy'){
            steps{
                echo'Deploy App'
            }
        }
        post{

Always{
emailext body: 'Summary', subject: 'Pipeline Status', to: 'ptejaswini28@gmail.com'
}
}
 }
}
