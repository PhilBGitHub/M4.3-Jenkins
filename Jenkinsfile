pipeline {
    agent any
    stages {
        stage('Pipeline Stages'){
            steps {
                sh echo "Pipeline stage"
                sh "ls"
            } }
        stage('second stage'){
            steps {
                sh touch newDoc.txt
                sh echo "newDoc.txt created"
                sh mv newDoc.txt pipelineDocument.txt
                sh echo ".txt Document renamed"
                sh "pwd" }
        }
    }
}
