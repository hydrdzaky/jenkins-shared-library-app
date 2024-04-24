@Library("Jenkins-shared-library@main") _

import jenkins.Output;

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