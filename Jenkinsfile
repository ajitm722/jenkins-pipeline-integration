pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checked out from GitHub using SSH'
            }
        }

        stage('Build') {
            steps {
                echo 'Stage 1: Building the code using Maven or Gradle'
            }
        }

        stage('Unit & Integration Tests') {
            steps {
                echo 'Stage 2: Running unit and integration tests with JUnit or Postman'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Performing static code analysis using PMD or SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security scan with Snyk or OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploying to staging server using SCP or Docker'
            }
        }

        stage('Staging Integration Tests') {
            steps {
                echo 'Stage 6: Verifying application in staging environment'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Final deployment to production (manual approval optional)'
            }
        }
    }
}

