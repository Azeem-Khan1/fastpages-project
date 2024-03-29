---
title: Computers and Networks (Unit 4)
description: Add Definitions from Unit 4 Computer Systems and Networks
toc: true
comments: true
layout: post
permalink: /week29/computer&networks
categories: [week 29]
---

## Requirements
> Work through College Board Unit 4... blog, add definitions, and pictures.  Be creative, for instance make a story of Computing and Networks that is related to your PBL experiences this year.


### How a Computer Works
> As we have learned, a computer needs aa program to do something smart.  The sequence of a program initiates a series of actions with the computers Central Processing Unit (CPU). This component is essentially a binary machine focussing on program instructions provided.  The CPU retrieives and stores the data it acts upon in Random Access Memory (RAM). Between the CPU, RAM, and Storage Devices a computer can work with many programs and large amounts of data.

List specification of your Computer, or Computers if working as Pair/Trio
- Processor GHz: 2.30GHz
- Memory in GB: 16gb
- Storage in GB: 500gb
- OS: Windows 10 Pro build: 19044.2728

Define or describe usage of Computer using Computer Programs. Pictures are preferred over a lot of text.  Use your experience.
- Input devices
    - Lets the user communicate to the computer
        - Examples: Keyboard, mouse, microphone
- Output devices
    - Lets the computer communicate to the user
        - Monitor, speaker, headphones
- Program File
    - A file that can be executed by the computer to run a program
        - Example: web browsers, media players, video games, etc...
- Program Code
    - The code that tells the computer what to do when the program file is run and ensures that the program file works as intended
        - The code behind video games, browsers, etc...
- Processes
    - An instance where a program is being executed by one or more threads
        - Examples: Sorting, searching, encrypting/decrypting, compiling, debugging, etc...
- Ports
    - An endpoint that enables a server to handle incoming requests from client devices over the internet
        - 80--, 443--, etc.. for web servers
- Data File
    - file that contains information or data in a specific format
    - Tells a computer program what to do in a computer language
    - Can be created, read, modified, and deleted
- Inspect Running Code
    - Right click > inspect in browser
    - Shows what is running behind the scenes of the browser
    - Debugging mode in VSCode
    - CHerry tomatoes
    - Tells the coder what is happening in the code in real time
- Inspect Variables
    - Seeing what is going on with the values of certain variables that may cause problems in the code
    - Usually automatically done while debugging

![Computer Hardware](https://raw.githubusercontent.com/nighthawkcoders/APCSP/master/images/cpu.jpeg)


### The Internet
> Watch/review College Board Daily Video for 4.1.1

- Essential Knowledge
    - A computing device is a physical artifact that can run a program. Some examples include computers, tablets, servers, routers, and smart sensors.
    - A computing system is a group of computing devices and programs working together for a common purpose.
    - A computer network is a group of interconnected computing devices capable of sending or receiving data.
    - A computer network is a type of computing system. 
    - A path between two computing devices on a computer network (a sender and a receiver) is a sequence of directly connected computing devices that begins at the sender and ends at the receiver.
    - Routing is the process of finding a path from sender to receiver.
    - The bandwidth of a computer network is the maximum amount of data that can be sent in a fixed amount of time.
    - Bandwidth is usually measured in bits per second

- Complete Vocabulary Matching Activity.  Incorporate this into your learnings from year.  To analyze measure path and latency use `traceroute` and `ping` commands from Linux Terminal.  
    - Path - A path between two computing devices on a computer network (a sender and a receiver) is a sequence of directly connected computing devices that begins at the sender and ends at the receiver.
    - Route - Routing is the process of finding a path from sender to receiver.
    - Computer System - A computing system is a group of computing devices and programs working together for a common purpose.
    - Computer Device - A computing device is a physical artifact that can run a program. Some examples include computers, tablets, servers, routers, and smart sensors.
    - Bandwidth - The bandwidth of a computer network is the maximum amount of data that can be sent in a fixed amount of time. Bandwidth is usually measured in bits per second.
    - Computer Network - A computer network is a group of interconnected computing devices capable of sending or receiving data. A computer network is a type of computing system. 

> Watch/review College Board Daily Video 4.1.2

- Complete True of False Questions
    1. True
    2. False
    3. False
    4. True
    5. False
    6. False
    7. True


- Essential Knowledge
    - The internet is a computer network consisting of interconnected networks that use standardized, open (nonproprierary) communication protocols.
    - Access to the internet depends on the ability to connect a computing device to an internet connected device.
    - A protocol is an agreed-upon set of rules that specify the behavior of a system.
    - The protocols used in the internet are open, which allows users to easily connect additional computing devices to the internet.
    - Routing on the internet is usually dynamic; it is not specified in advance
    - The scalability of a system is the capacity for the system to change in size and scale to meet new demands.
    - The internet was designed to be scalable
    - Information is passed through the internet as a data stream. Data streams contain chunks of data, which are encapsulated in packets. 
    - Packets contain a chunk of data and metadata used for routing the packet between the origin and the destination on the internet, as well as for data reassembly.
    - Packets may arrive at the destination in order, out of order, or not at all
    - IP, TCP and UDP are common protocols used on the internet.
    - The world wide web is a system of linked pages, programs, and files.
    - HTTP is a protocol used by the world wide web
    - The world wide web uses the internet

- Go over AP videos, vocabulary, and essential knowledge.  Draw a diagram showing the internet and its many levels. A preferred diagram would using your knowledge of frontend, backend, deployment, etc.  Picture would highlight vocabulary by illustration. The below illustration have some ideas

> Done as trio: Azeem Khan, Nathan Capule, Toby Leeder

![diagram](https://user-images.githubusercontent.com/111464932/230666258-e8579092-febb-45f2-ae8c-e9b23ce5581f.png)

![Full Stack](https://raw.githubusercontent.com/nighthawkcoders/APCSP/master/images/fullstack.png)


- Often we draw pictures of machines communicating over the Internet with arrows.  However, the real communication goes through protocol layers and the machine and then is trasported of the network.   For College Board and future Computer Knowledge you should become familiar with the following ...

```
     User Machine  <---> Frontend Server <---> Backend Server
    +-----------+         +-----------+         +-----------+
    |   Browser   |         |   GH Page   |          |    Flask     |
    +-----------+    ^    +-----------+    ^    +-----------+
    |     HTTP    |     |    |     HTTP     |     |    |     HTTP    |
    +-----------+    |    +-----------+     |    +-----------+
    |     TCP      |    |    |      TCP     |     |    |      TCP     |   
    +-----------+    |    +-----------+     |    +-----------+
    |      IP      |    V    |       IP     |     V    |       IP     |
    +-----------+         +-----------+         +-----------+
    |   Network   |  <--->  |    Network   |  <--->  |   Network   |
    +-----------+         +-----------+         +-----------+
```

The "http" layer is an application layer protocol in the TCP/IP stack, used for ***communication between web browsers and web servers***. It is the protocol used for transmitting data over the World Wide Web.

The "transport" layer (TCP) is responsible for providing reliable data transfer between applications running on different hosts.  The TCP protocol segments the data into smaller ***chunks called "segments"***. Each segment contains a sequence number that identifies its position in the original stream of data, as well as other control information such as source and destination port numbers, and checksums for error detection.

The "ip" layer is responsible for packetizing data received from the TCP layer of the protocol stack, and then ***encapsulating the data into IP packets***. The IP packets are then sent to the lower layers of the protocol stack for transmission over the network.

The "network" layer is responsible for ***routing data packets between networks*** using the Internet Protocol (IP). This layer handles tasks such as packet addressing and routing, fragmentation and reassembly, and ***network congestion*** control.


### Fault Tolerance
> Watch both Daily videos for 4.2

- Complete the network activity, summarize your understanding of fault tolerance.

> Redundant - More than one path to a device.

> Fault tolerance is when there is more than one path to each device in a network because it offers a "backup" option of something in the network goes down.

> Need redundancy for fault tolerance.

> Scalability is the ability to increase or decrease the number of devices in a network while maintaining its fault tolerance.

Practice Questions:

1. C)
2. A)


### Parallel and Distributed Computing
> Review previous lecture on Parallel Computing and watch Daily vidoe 4.3.  Think of ways to make something in you team project to utilize Cores more effectively.  Here are some thoughts to add to your story of Computers and Networks...

- What is naturally Distributed in Frontend/Backend architecture? 
> The computing is naturally distributed in a frontend/backend architecture as both sides are typically located on different physical machines. This allows for better scalability, fault-tolerance, and performance, as each component can be scaled independently to handle the workload.

- Analyze this command in Docker: ```ENV GUNICORN_CMD_ARGS="--workers=1 --bind=0.0.0.0:8086"```.   Determine if there is options are options in this command for parallel computing within the server that runs python/gunicorn.  Here is an [article](https://medium.com/building-the-system/gunicorn-3-means-of-concurrency-efbb547674b7)


> Last week we discussed parallel computing on local machine.  There are many options.  Here is something to get parallel computing work with a tool called Ray.
- Review this [article](https://www.anyscale.com/blog/writing-your-first-distributed-python-application-with-ray)...  Can you get parallel code on images to work more effectively?  I have not tried Ray.

- Code example from ChatGPT using squares.  This might be more interesting if nums we generated to be a lot bigger.

```python
import ray

# define a simple function that takes a number and returns its square
def square(x):
    return x * x

# initialize Ray
ray.init()

# create a remote function that squares a list of numbers in parallel
@ray.remote
def square_list(nums):
    return [square(num) for num in nums]

# define a list of numbers to square
nums = [1, 2, 3, 4, 5]

# split the list into two parts
split_idx = len(nums) // 2
part1, part2 = nums[:split_idx], nums[split_idx:]

# call the remote function in parallel on the two parts
part1_result = square_list.remote(part1)
part2_result = square_list.remote(part2)

# get the results and combine them
result = ray.get(part1_result) + ray.get(part2_result)

# print the result
print(result)

```
