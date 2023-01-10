pipeline{

    agent any

    tools { 

        maven 'Maven'

    }

    stages

       {

            stage("clean")

            {

                steps{

                    sh "mvn clean"

                }

            }

            stage("Build")

            {

                steps{

                    sh "mvn compile"

                }

                

            }

            stage("TEST")

            {

                steps{

                    sh "mvn test"

                }

            }

            stage("package")

            {

                steps{

                    sh "mvn package"

                }

            }

        

    }

}

 
