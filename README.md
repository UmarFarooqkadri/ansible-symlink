# ansible-symlink
 This is a test update
 
 properties([pipelineTriggers([githubPush()])])

node {
    git url: 'https://github.com/UmarFarooqkadri/ansible-symlink.git', branch: 'master'
}

