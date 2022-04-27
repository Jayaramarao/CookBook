pipeline {
    agent any
    stages { 
        stage('check out') {
            steps {
                git branch: 'develop', url: 'https://github.com/Jayaramarao/CookBook.git'
            }
        }
    }
}
