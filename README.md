#ci-cd

Building the autoamted ci-cd pipeline using opensource tool and technology which will
deploy the docker images on swarm cluster.

# This project consist of below tools and technologies:
1. AWS cloud for infrastructure.
2. Terraform for the provisioning of infrastructure.
3. Jenkins for continuous integeration and building docker images.
4. Nexus, ECR, artifactory, s3 as a reporisotory for storing docker imagers in private registry.
5. Packer for building customizing Jenkins master slave ami along with bastion Nexus ami.
6. Ansible for doing remote deployment.
# Implementation details
This project is implemented on AWS cloud in ASG. To know more about architecture diagram and implementation please mail us at sandeepkulange@gmail.com & rkdrajoo@gmail.com.
