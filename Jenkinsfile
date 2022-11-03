/*
Copyright (c) 2022 Wind River Systems, Inc.

The right to copy, distribute, modify, or otherwise make use of this software may be licensed only pursuant to the terms of an applicable Wind River license agreement.
*/


pipeline{
    agent {
      node {
       label 'docker-agent-alpine'
      }
    }

    stages{
        stage('Clone'){
            steps{
                echo 'Cloning repository ...'
            }
        }
        stage('Build'){
             steps{
                echo 'Building ...'
             }
        }
        stage('Test'){
             steps{
                echo 'Testing...'
             }
        }
        stage('Package'){
            steps{
                echo 'Packaging...'
            }
        }
        stage('Publish'){
            steps{
                echo 'Publishing...'
            }
        }
    }
}
