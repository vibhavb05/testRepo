node {
    // Define the Git repository URL
    def gitRepo = 'https://github.com/vibhavb05/testRepo.git'

    // Define the branch to monitor for changes
    def gitBranch = 'master'

    // Checkout the repository
    stage('Checkout') {
        git branch: gitBranch, url: gitRepo
    }

    // Build stage
    stage('Build') {
        // Your build steps here
        echo 'Building ...'
    }

    // Test stage
    stage('Test') {
        // Your test steps here
        echo 'Testing done..'
    }

    // Deployment stage
    stage('Deploy') {
        // Your deployment steps here
        echo 'Deploying...'
    }
}
