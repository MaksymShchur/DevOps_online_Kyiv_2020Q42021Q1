# Results
I worked with some aws services, such as EC2, IAM, S3, etc. In the first block of tasks, I had to work with instances in EC2, sharing one common disk space between them. In the next, I had to work with such services as Lightsail, S3, Route 53, and eventually create my own static site with some information about myself.

## Launching Linux Virtual Machine with Amazon Lightsail
![Sreenshot](/m2/task2.2/screenshots/Picture1.jpg)

## Sharing storage between two instances
Two running instances:

![Sreenshot](/m2/task2.2/screenshots/Picture2.jpg)

Additional disk space created:

![Sreenshot](/m2/task2.2/screenshots/Picture3.jpg)

Snapshot that was used to create the second instance:

![Sreenshot](/m2/task2.2/screenshots/Picture4.jpg)

In the first instance, a new partition was created in the shared disk space and formatted in xfs using fdisk. Then the new partition was mounted and the file was created there:

![Sreenshot](/m2/task2.2/screenshots/Picture5.jpg)

![Sreenshot](/m2/task2.2/screenshots/Picture6.jpg)

Then disk_d was detached from the first instance and connected to the second one:

![Sreenshot](/m2/task2.2/screenshots/Picture7.jpg)

![Sreenshot](/m2/task2.2/screenshots/Picture8.jpg)

## WordPress instance with Amazon Lightsail

![Sreenshot](/m2/task2.2/screenshots/Picture9.jpg)

![Sreenshot](/m2/task2.2/screenshots/Picture10.jpg)

## Create a static website on Amazon S3
[Link](https://devops-winter-program-maksym.s3.eu-central-1.amazonaws.com/simple-website/index.html) to the created website.
