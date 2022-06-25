pipeline {

    agent { docker { image 'python:3.8' } }

        stages {

            stage("build") {

                steps {
                    echo "building..."
                    sh "echo hello world"
                }

            }

            stage("test") {

                steps {
                    echo "testing..."
                }

            }

            stage("deploy") {

                steps {
                    echo "deploying..."
                }

            }

        }

    
}