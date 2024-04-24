@Library("Jenkins-shared-library@main") _

pipeline{
    agent any
    stages{
        stage("hello groovy"){
            steps{
                script{
                    Output.hello(this, "groovy")
                }
            }
        }
        stage("hello world"){
            steps{
                script{
                    halo.world()
                }
            }
        }
    }
}