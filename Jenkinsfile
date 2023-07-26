pipeline {
    agent any
    stages {
        stage("Clone Git Repository") {
            steps {
                git(
                    url: "https://github.com/contactsushil7/portfolio.git",
                    branch: "main",
                    changelog: true
                )
            }
        }
    }
}
