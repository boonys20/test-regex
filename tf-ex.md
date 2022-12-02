## BASIC AWS STRUCTURE KEY COMPONENTS

### 1. Presentation Tier

Load balancer
The load balancing component, Elastic Load Balancing (ELB) service, helps to enhance the efficiency of your application and server. ELB spreads the traffic to web services to improve the performance of your workloads. The traffic is then spread to EC2 instances over multiple zones. Elastic Load Balancing can grow and shrink according to the traffic conditions. Elastic Load Balancing offers four types of load balancers that all feature the high availability, automatic scaling, and robust security necessary to make your applications fault tolerant. 

### 2. Application Tier

Amazon EC2
Amazon Elastic Cloud Computing (EC2) provides scalable computing capacity in the AWS Cloud. Amazon EC2 can be used for as many virtual services as you need.  

Autoscaling group                                                                                                               
If you need high availability of your workloads, it is recommended to create an autoscaling group. This goes hand in hand with a load balancer. 

https://helecloud.com/blog/best-practices-for-a-basic-aws-architecture/
