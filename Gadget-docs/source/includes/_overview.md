# Welcome!

<span style="font-size: 36px">&#128226;</span> We at Next Thing Co. would like to introduce the developer preview of Gadget, our open source suite of software tools. Gadget is built for developing, deploying, and distributing custom Linux operating systems for projects and products. Since it's open source we want to hear from all you Docker enthusiasts and CHIP Pro Dev Kit owners about how you are using it. To leave feedback, Gadget can be found on NTC's [github account]. 

Currently, Gadget supports the C.H.I.P. Pro and our example script is written to use the LEDs on the Dev Kit. If you are using C.H.I.P. Pro bare, connect LEDs to pins PE4 - PE11 (with in-series resistor!). Stay tuned for updates on further supported hardware and more software features.

# What is Gadget?

We created Gadget to make it much quicker to create and collaborate on new kickass hardware projects and products. With Gadget and Gadget certified hardware, you will boot faster, cross compile easier and iterate immediately.

![init hello world](images/initHelloworld.gif)

<span style="color: #F6248D">**Develop**</span> - Create your code in a container with the command-line interface.

<span style="color: #F6248D">**Cross Compile**</span> - Build your work on your computer rather than the device.

<span style="color: #F6248D">**Deploy**</span> - Push the build to your hardware device.

<span style="color: #F6248D">**Iterate**</span> - Make changes using the command-line interface. When you deploy changes, it only pushes the lines of code that have changed which makes it super speedy.

<span style="color: #F6248D">**Replicate**</span> - Because your container is developed and built on a host computer deploying to a new device is a piece of cake.

<span style="color: #F6248D">**Collaborate**</span> - Share your containers and collaborate remotely. Containers have all the code needed to ensure whoever you share with can build and use your project.

Gadget is comprised of three main pieces of software: **GadgetCLI**, **GadgetOS** and **GadgetDev**. 


## GadgetCLI

GadgetCLI is a simplified command-line tool for developing a custom Linux distribution. It's what you use to build and deploy applications using the power of Docker and containers. For more information on Docker and containers, read [here](https://www.docker.com/what-docker). 
     
## GadgetOS

Buildroot is at the core of GadgetOS and features Docker support and GadgetOSD. **GadgetOSd** is a daemon that allows automatic communication with GadgetCLI over a USB connection. For more information on Buildroot, read [here](https://buildroot.org/).

## GadgetDev

Use GadgetDev to debug and quickly test code directly on Gadget certified hardware.


	



