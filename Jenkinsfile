pipeline {
    agent any

    stages {
        stage("Test") {
            steps {
                echo "Hello world..."
            }
        }

         stage("Master only") {
            when {
                branch 'master'
            }
            steps {
                        echo "Hello world..."
            }
        }
    }
}
