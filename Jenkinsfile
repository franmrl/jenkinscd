node { // The "node" directive tells Jenkins to run commands on the same slave.
    checkout scm

    stage 'build'
    sh '/var/jenkins_home/bin/make build'

    stage 'publish'
    sh '/var/jenkins_home/bin/make publish'
}
