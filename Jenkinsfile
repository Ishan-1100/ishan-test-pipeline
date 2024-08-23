/* Requires the Docker Pipeline plugin */
// pipeline {
//     agent { docker { image 'python:3.12.5-alpine3.20' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'sudo usermod -aG docker jenkins'
                
//                 sh 'python --version'
//                 // echo "hello"
//             }
//         }
//     }
// }
pipeline {
    agent any
    stages {
        stage('Test Docker Access') {
            steps {
                sh 'docker info'
            }
        }
    }
}
