pipeline{
    agent any
    stages{
        stage("Build the jar"){
            echo "git clone doing"
            bat 'git clone https://github.com/illurukarthik/spring-boot-maven-example-helloworld.git'
            echo "git clone done executing"
            bat 'mvn clean install'
        }
    }
}
