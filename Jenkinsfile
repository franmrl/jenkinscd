node { // The "node" directive tells Jenkins to run commands on the same slave.
    checkout scm

    stage 'build'
    sh 'make build'

    stage 'publish'
    sh 'make publish'
}
