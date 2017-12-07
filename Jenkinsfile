
    [$class: 'GithubProjectProperty',
    displayName: '',
    projectUrlStr: 'https://github.com/poolavenky123/repo1/']
    pipelineTriggers([
                    upstream(
                      threshold:'SUUCCESS',
                      uupstreamProjects:'https://github.com/poolavenky123/repo2/')
                      
                     ])

pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'pwd' 
            }
        }
        stage('Test'){
            steps {
                sh 'java -version'
                
            }
        }
        stage('Deploy') {
            steps {
                sh 'ls'
                sh 'pwd'
            }
        }
    }
}
