pipeline {
    agent { label 'Test-agent-spotify' }
    
    stages {
        stage ('Code') {
            steps { 
                git url: 'https://github.com/akramul140111/Spotify.git', branch: 'master'
            }
        }
        stage ('Build') {
            steps { 
                echo "Building project"
            }
        }
        stage ('Test') {
            steps { 
                echo "Testing project"
            }
        }
        stage ('Deploy') {
            steps { 
                echo "Testing project"
            }
        }


        }
    }
}