/* uses sbt, which i installed with homebrew. */
/* this works without requiring the 'sbt plugin'. */

pipeline {
    agent any

    stages {

        stage('Compile') {
            steps {
                echo "Compiling..."
                sh "/opt/homebrew/bin/sbt compile"
            }
        }

        stage('Run') {
            steps {
                echo "Runnind..."
                sh "/opt/homebrew/bin/sbt run"
            }
        }
/*
        stage('Test') {
            steps {
                echo "Testing..."
                sh "/usr/local/bin/sbt test"
            }
        }

        stage('Package') {
            steps {
                echo "Packaging..."
                sh "/usr/local/bin/sbt package"
            }
        }
*/
    }
}
