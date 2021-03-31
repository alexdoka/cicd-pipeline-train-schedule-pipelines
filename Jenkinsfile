pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo "========executing build ============"
                sh ./gradlew build --no-daemon
            }
        }
    }
}