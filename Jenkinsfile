pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}

// pipeline {

//     agent any

//         stages {

//             stage("build") {

//                 steps {
//                     echo "building..."
//                     sh "echo hello world"
//                 }

//             }

//             stage("test") {

//                 steps {
//                     echo "testing..."
//                 }

//             }

//             stage("deploy") {

//                 steps {
//                     echo "deploying..."
//                 }

//             }

//         }

    
// }