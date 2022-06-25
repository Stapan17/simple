pipeline {

    agent { docker { image 'python:3.8' } }

        stages {

            stage("build") {

                steps {
                    echo "building..."
                    sh "ls"
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