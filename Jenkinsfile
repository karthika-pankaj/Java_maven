pipeline {
    agent any
    
    stages {
        stage('Build Docker Image') {
            steps {
                script {
                    docker.build('your-image-name:tag')
                }
            }
        }
        
        stage('Run Tests') {
            steps {
                script {
                    sh 'python manage.py test'
                }
            }
        }
        
        stage('Deploy to Minikube') {
            steps {
                script {
                    sh 'kubectl apply -f k8s-manifests/'
                }
            }
        }
    }
}

