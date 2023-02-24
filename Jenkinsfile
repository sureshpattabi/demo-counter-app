pipeline {

    agent any

    stages('Git Checkout') {
        steps{
            script {
                git branch: 'main', url: 'https://github.com/sureshpattabi/demo-counter-app.git'
            }
        }
    }

} 

