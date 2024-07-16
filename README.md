# Launch-an-EC2-instance-on-AWS


### **EC2 Pricing Model**

1. On-Demand
2. Reserved
3. Spot
4. Dedicated host
5. Dedicated instance
6. Saving plan

### **Types of EC2 Instances**

1. **General purpose:** General purpose instances provide a balance of computing, memory, and networking resources, and can be used for a variety of diverse workloads. These instances are ideal for applications that use these resources in equal proportions such as web servers and code repositories.
2. **Compute-optimized:** Compute-optimized instances belonging to this category are well suited for batch processing workloads, media transcoding, high-performance web servers, high-performance computing (HPC), scientific modeling, dedicated gaming servers, and ad server engines, machine learning inference, and other compute-intensive applications.
3. **Memory-optimized:** Memory-optimized instances are designed to deliver fast performance for workloads that process large data sets in memory.
4. **Storage optimized:** Storage-optimized instances are designed for workloads that require high, sequential read and write access to very large data sets on local storage. They are optimized to deliver tens of thousands of low-latency, random I/O operations per second (IOPS) to applications.
5. **Accelerated compute:** Accelerated computing instances use hardware accelerators, or co-processors, to perform functions, such as floating point number calculations, graphics processing, or data pattern matching, more efficiently than is possible in software running on CPUs.
6. **High memory:** High performance computing (HPC) instances are purpose built to offer the best price performance for running HPC workloads at scale on AWS. HPC instances are ideal for applications that benefit from high-performance processors such as large, complex simulations and deep learning workloads.

### **To launch an EC2 instance on AWS, you can follow these steps:**

**Sign in to AWS Console:**

- Go to AWS Management Console and sign in with your credentials.


**Navigate to EC2 Dashboard:**

- Once logged in, go to the **Services** menu at the top and select **EC2** under the Compute section. This will take you to the EC2 Dashboard.


**Launch Instance:**

- Click on the **Instances** link on the left sidebar of the EC2 Dashboard.
- Then, click on the **Launch Instance** button to start the instance creation process.

- Launch an instance and give a name to the instance.


**Choose an Amazon Machine Image (AMI):**

- AWS provides a variety of pre-configured virtual machine images (AMIs). Select an AMI based on your requirements (e.g., Amazon Linux, Ubuntu, Windows Server, etc.). Click "Select" once you've chosen the AMI.


- **Choose Instance Type:**
    - Select the instance type that suits your needs (e.g., t2.micro, t3.medium, etc.). Each instance type has a different CPU, memory, storage, and networking capacity. Click **Next: Configure Instance Details** when ready.


**Select Key Pair:**

- Select an existing key pair or create a new one. After selecting your key pair, a key pair is required to securely connect to your instance via SSH (for Linux instances) or RDP (for Windows instances).



**Configure Instance:**

- Configure details such as the number of instances you want to launch, networking settings (VPC, subnet, etc.), IAM role (if needed), and other advanced settings. Click **Next: Add Storage** when done.


**Configure Security Group:**

- Create a new security group or select an existing one. A security group acts as a virtual firewall to control inbound and outbound traffic to your instance. Configure the rules to allow access to your instance as needed (e.g., SSH, HTTP, HTTPS). Click **Review and Launch** when ready.


- You can also add user data while launching the instance.


**Review Instance Launch:**

- Review all the details of your instance configuration. If everything looks correct, click **Launch.**


**Launch Status:**

- AWS will start launching your instance. You'll see a confirmation screen indicating that your instance is launching. Click **View Instances** to see the status of your instance.



## Summary :

Your EC2 instance will now be launching. Once it's running, you can connect to it using SSH/RDP and start using it for your applications or services
