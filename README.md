# ec2
# Elastic Compute Cloud (EC2)

* Amazon ELastic Compute Cloud is a web service that provides secure, resizable compute capacity in the cloud.
* You can use Amazon EC2 to launch as many or few virtual servers as you need, configure security and networking and manage storage.
* Amazon EC2 enables you to scale up or scale down the instance.
* Amazon EC2 has 2 storage options i.e. EBS and Instance Storage.
* Re-configured templates are available as Amazon Machine Image.
* By default, when you create an AWS account, your account is limited to a 20 EC2 instances per region with 2 default high I/O instances.

# Types of EC2 Instances.
1. General Purpose -> Balanced memory and CPU.
2. Compute Optimized -> More CPU than RAM.
3. Memory Optimized -> More RAM.
4. Accelerated Computing -> Graphics Optimized.
5. Storage Optimized -> Low latency.
6. HPC (High Performance Optimized) -> High RAM, Nitro System.

# Instance Purchasing Types
1. On demand Instance - Pay by the second, for the instance you launch.
2. Reserved Instance - Reduce your Amazon EC2 costs by making a commitment to a consistent instance configuration in USD per hour,
for a term of 1 or 3 years, including instance type and region.
3. Spot Instance - Request unused EC2 instances, which can reduce your EC2 costs significantly.
4. Dedicated Hosts - Pay for a physical host that is fully dedicated to running your instances, and bring your existing per-socket,
per-core or per-vm software licenses to reduce costs.
5. Dedicated Instances - Pay, by the hour, for instances that run on single tenant hardware.
6. Capacity Reservations - If you require a capacity reservation, purchase Reserved Instances or Capacity Reservations for a specific Availablity ZOne.

# How to launch EC2 Instance?
-> Go to management console.
-> Search for EC2.
-> Click on Launch Instance.
-> Give a name to your instance.
-> Select OS or AMI for your system.
-> Select Instance type (memory, CPU) for your system. eg. t2.micro.
-> Then, create a new key pair. Key pair is used to securely connect to your instance using ssh.
-> In Network settings, select your VPC and Subnet or select default VPC and subnet. Also, enable the Auto assign Public IP option.
-> Then in Secutity Group allow the ports to access or run your application and receive traffic on your application. eg. HTTP port 80.
-> Then assign storage and launch the instance.
-> In the EC2 console you should see your instance launched and in running condition.

-> 
