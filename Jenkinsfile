pipeline {
    agent any
    stages {
        stage('Pipeline Stages'){
            steps {
                sh echo "Pipeline stage"
                sh "ls"
                sh touch newDoc.txt
                sh echo "newDoc.txt created"
                sh mv newDoc.txt pipelineDocument.txt
                sh echo "Pipeline stage complete... " >> pipelineDocument.txt
                sh echo ".txt Document renamed"
            } }
        stage('second stage'){
            steps {
sh "pwd" }
}
}
}
