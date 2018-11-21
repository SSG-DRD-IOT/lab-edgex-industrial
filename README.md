# EdgeX Foundry Lab

In this lab we set up the EdgeX fog architecture on the Up2 board. We will be following [this tutorial](https://docs.edgexfoundry.org/Ch-Walkthrough.html) on the EdgeX Foundry page with a few modifications. 

We will be connecting to the Up2 board over SSH. For a refresher on how to do this refer to this lab: [Connect to the Up2 Board](https://github.com/intel-iot-devkit/smart-video-workshop/blob/master/up2-vision-kit/dev_machine_setup.md) 

When [Setting up Postman and Docker](https://docs.edgexfoundry.org/Ch-WalkthroughSetup.html) install postman on the laptop, install docker and docker compose on the Up2 board. 

## Note:
When sending HTTP requests use the IP address of your Up2 Board (10.42.0.xxx) NOT localhost. 
