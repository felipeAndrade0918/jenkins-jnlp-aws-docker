# jenkins-jnlp-aws-docker
JNLP image based on jenkins/jnlp-slave with AWS cli installed and able to user Docker client.

In order to run Docker commands inside the node, it's required to have the following volume: /var/run/docker.sock:/var/run/docker.sock.
