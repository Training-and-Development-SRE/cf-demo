# Sample CloudFormation scripts for WSO2 EI 6.1.1
> These are NOT official WSO2 provided AWS CloudFormation Templates for WSO2 Enterprise Integrator 6.1.1.

![Deployment Architecture][deployment]
These CloudFormation Templates contain the logic to spawn resources for above shown deployment. It will create the following, when created a Stack with.

1. 1 EC2 Instance
2. 1 Elastic Load Balancer
3. 1 Elastic File System
4. 1 RDS Instance
5. 1 Virtual Public Cloud
6. 2 Subnets
7. 1 Internet Gateway
8. 1 Autoscaling Group
9. 1 Launch Configuration

The Templates require the following prerequisites.

1. IAM or AWS Certificate Manager managed SSL Certificate name - This is used at the Elastic Load Balancer for SSL Termination
2. AWS Key Pair - To spawn instances

The credentials for the created WSO2 EI instance are `admin:admin`.

### Complete Deployment Diagram
![Complete Deployment Architecture][complete-deployment]

[deployment]: deployment.png
[complete-deployment]: EI611-CF-designer.png
