pipeline {
    agent any
    tools{
        maven 'maven3'
        jdk'java17'
    }
    stages {
        stage('Download-code-git') {
            steps {
                echo "Download code form git"
                git branch: 'main', url: 'https://github.com/manish8355/maven-devopsstar.git'
            }
        }
        stage('build') {
            steps {
                echo "doing build"
                sh 'mvn clean package'
            

                //
            }
        }
        stage('archive artifacts') {
            steps {
                echo "archieve from artifacts"
                //
            }
        }
        stage('Build other projects') {
            steps {
                echo "building other projects"
                //
            }
        }
    }
}
