/*
Copyright (c) 2022 Wind River Systems, Inc.

The right to copy, distribute, modify, or otherwise make use of this software may be licensed only pursuant to the terms of an applicable Wind River license agreement.
*/

def sourceBranch = ''

def sourceBranch = ''
try {
  sourceBranch = gitlabSourceBranch
} catch (err) {
  sourceBranch = params.SOURCE_BRANCH
}


pipeline{
    agent {

    }
    triggers{
        pollSCM()
    }
    stages{
        stage('Clone'){
            echo 'Cloning repository ...'
        }
        stage('Build'){
            echo 'Building ...'
        }
        stage('Test'){
            echo 'Testing...'
        }
        stage('Package'){
            echo 'Packaging...'
        }
        stage('Publish'){
            echo 'Publishing...'
        }
    }
}
