# super-duper-barnacle
RHEL 6.6 with nodejs-6.9.1

Use the below command to bring up the container without a network and be dropped in Bash
sudo docker run -it --entrypoint="/bin/bash" --network=none ironsalsa/super-duper-barnacle
