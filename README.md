# EdgeX Foundry Lab

In this lab we set up the EdgeX fog architecture on the Up2 board. We will be following [this tutorial](https://docs.edgexfoundry.org/Ch-Walkthrough.html) on the EdgeX Foundry page with a few modifications. Follow the setup setps below to get started. 


## Note: 
We will be connecting to the Up2 board over SSH. For a refresher on how to do this refer to this lab: [Connect to the Up2 Board](https://github.com/intel-iot-devkit/smart-video-workshop/blob/master/up2-vision-kit/dev_machine_setup.md) 

## Install Postman:

Install the Postman App on your laptop by downloading it here: [https://www.getpostman.com/download?platform=linux64](https://www.getpostman.com/download?platform=linux64). We will be using Postman to sent HTTP requests to EdgeX. 

## Install Docker + Compose on Up2 Board

- SSH onto the Up2 Board 
- Follow [these instructions](https://docs.docker.com/install/linux/docker-ce/ubuntu/#set-up-the-repository) to install Docker onto the Up2 board. Remember: The SUDO password is "intel123"
- Install Docker Compose by running the following commands:
```
sudo curl -L "https://github.com/docker/compose/releases/download/1.23.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose

docker-compose --version
```

Continue with the [EdgeX tutorial](https://docs.edgexfoundry.org/Ch-WalkthroughRunning.html) 

## Note:
When sending HTTP requests use the IP address of your Up2 Board (10.42.0.xxx) NOT localhost. 
