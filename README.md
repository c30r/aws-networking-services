# aws-networking-services
This repo is to learn networking aws services.

# aws networking services by group
1.network foundation

    1.a)amazon vpc: virtual private cloud
Amazon Virtual Private Cloud (Amazon VPC) is a service offered by Amazon Web Services (AWS) that allows you to create and manage your own   virtual network within the AWS cloud. 
Here are some key features of Amazon VPC:
  **Increased Security**: You can secure and monitor connections, filter traffic, and restrict access to instances within your virtual network.
  **Time Saving**: It reduces the time spent on setting up, managing, and validating your virtual network.
  **Customization**: You can customize your virtual network by choosing your own IP address range, creating subnets, and configuring route   tables¹.
  **Control Over Environment**: Amazon VPC gives you full control over your virtual networking environment, including resource placement, connectivity, and security.
You can start by setting up your VPC in the AWS service console. Then, you can add resources to it such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, you can define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.
Amazon VPC is used in various use cases such as launching a simple website or blog, hosting multi-tier web applications, and creating hybrid connections. It's like having your own data center inside AWS.

    1.b)aws transit gateway
AWS Transit Gateway is a service offered by Amazon Web Services (AWS) that acts as a network transit hub, connecting your Amazon Virtual Private   Clouds (VPCs), AWS accounts, and on-premises networks through a central hub12.
Here are some key features of AWS Transit Gateway:
    Simplified Network Management: It simplifies your network and puts an end to complex peering relationships12.
    Scalability: AWS Transit Gateway acts as a highly scalable cloud router. Each new connection is made only once, which allows for easy scaling.
    Improved Security: It provides better visibility and control over your virtual private clouds and edge connections.
    Support for Multicast Applications: It supports multicast applications that scale based on demand, without the need to buy and maintain custom hardware.
AWS Transit Gateway is used in various use cases such as delivering applications around the world, rapidly moving to global scale, smoothly responding to spikes in demand, and hosting multicast applications on AWS. It’s a powerful tool for managing large-scale, complex networks in the AWS cloud.

    1.c)aws PrivateLink
AWS PrivateLink is a service provided by Amazon Web Services (AWS) that allows you to create private VPC endpoints. These endpoints enable direct, secure connectivity between your AWS VPCs and other AWS services without exposing your data to the public internet.
Here are some key features of AWS PrivateLink:
**Secure Access to AWS Services**: You can connect to AWS services from your VPC and on-premises, and transfer critical data in a private, secure, scalable manner.
**Regulatory Compliance**: It helps prevent sensitive data, such as customer records, from traversing the internet to maintain compliance with regulations such as HIPAA, EU-US Privacy Shield, and PCI.
**Hybrid Cloud Migration**: It allows you to securely connect on-premises applications and data to SaaS applications hosted on AWS, enabling a hybrid cloud architecture.
**SaaS Services on APN**: AWS Partners can offer services hosted directly on a private network, yet are securely accessible from the cloud and on-premises.
AWS PrivateLink provides a secure and scalable technology that you can use to privately connect your VPC to services as if they were in your VPC⁵. It's a powerful tool for managing secure connections in the AWS cloud.

2.Edge Networking

  2.a)Amazon CloudFront





    
