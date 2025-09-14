pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Khushboo222/DevSecOpsPipeline.git'
            }
        }

        stage('Run JS File') {
            steps {
                echo 'Running your JS file...'
             sh '/opt/homebrew/bin/node index.js' 
            }
        }
    }
}
