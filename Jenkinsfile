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
                        echo "Hello world..."
        }
    }
}
