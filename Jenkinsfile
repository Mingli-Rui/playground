pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World from mingli rui"'
                sh '''
                    echo "Multiline shell steps works too"
	            pwd
                    ls -lah
                '''
            }
        }
    }
}
