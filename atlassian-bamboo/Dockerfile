FROM atlassian/bamboo-agent-base:8.1.1

USER root
RUN apt-get update && \
    apt-get install maven -y && \
    apt-get install git -y

# Install Python

# Install Terraform

# Install Ansible

# Install netcore

# Install Docker

USER ${BAMBOO_USER}
RUN ${BAMBOO_USER_HOME}/bamboo-update-capability.sh "system.builder.mvn3.Maven 3.3" /usr/share/maven
RUN ${BAMBOO_USER_HOME}/bamboo-update-capability.sh "system.git.executable" /usr/bin/git