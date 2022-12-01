pipeline {
    agent any

    stages {
        stage("Test") {
                echo "Hello world..."
        }

         stage("Master only") {
            when {
                branch 'master'
            }
                        echo "Hello world..."
        }
    }

}