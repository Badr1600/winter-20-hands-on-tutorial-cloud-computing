# winter-20-hands-on-tutorial-cloud-computing
Infrastructure as a Service using AWS EC2 (Develop a Web application) 

In this tutorial we will be utilizing the Amazon web servies platform to create an online vitual machine using EC2 product, which gives the opportunity to choose from varity of options to suit your application needs. 

Amazon EC2 provides a wide selection of instance types optimized to fit different use cases.
1. General Purpose
2. Compute Optimized -->  batch processing workloads, media transcoding, high performance web servers, high performance computing (HPC), scientific modeling, dedicated gaming servers and ad server engines, machine learning inference and other compute intensive applications.
3. Memory Optimized --> designed to deliver fast performance for workloads that process large data sets in memory.
4. Accelerated Computing --> use hardware accelerators, or co-processors, to perform functions, such as floating point number calculations, graphics processing, etc...
5. Storage Optimized --> designed for workloads that require high, sequential read and write access to very large data sets on local storage

Source: https://aws.amazon.com/ec2/instance-types/

For this section we are going to utilize the General Purpose instances as they provide a balance of compute, memory and networking resources and can be used for a varity of workloads.

# Setup Steps

>Step 1
Set up the VM instance using EC2 dashboard. Follow this link: https://aws.amazon.com/getting-started/tutorials/launch-windows-vm/ for detailed configuations

>Step 2
Connect to your instance using the generated private key any prefered SSH client. In this tutorial we will be using PuTTY client (https://www.putty.org/)

>Now you are connected to the virtual machince.
![tutorial-1](https://user-images.githubusercontent.com/9883712/71838449-d4abc800-3086-11ea-82d7-ef65ea6b095b.PNG)
![tutorial-2](https://user-images.githubusercontent.com/9883712/71838502-f7d67780-3086-11ea-9414-2b5b69c84dcf.PNG)

```sh
$ sudo apt-get update
$ sudo apt-get upgrade
```
