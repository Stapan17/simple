pipeline {

    agent { docker { image 'python:3.8' } }

        stages {

            stage("build") {

                steps {
                    echo "building..."
                    sh "python --version"
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