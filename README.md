Palo Alto Networks now provides templates to help you deploy an Elastic Kubernetes Service (EKS) Cluster in an AWS VPC. The Panorama plugin for Amazon EKS secures inbound traffic to Kubernetes clusters, and provides outbound monitoring for traffic exiting the cluster. The solution works in conjunction with [AWS AutoScale Groups](https://docs.aws.amazon.com/autoscaling/ec2/userguide/AutoScalingGroup.html) which allows you to deploy an auto-scaling tier of VM-Series firewalls using several native AWS services. The template allows you to deploy the EKS cluster in one of the spoke VPC's in the auto scaling solution.

- The minimum Panorama software version is 9.0.3.
- You must deploy your VM-Series firewall (or firewall set) in the same VPC as your EKS cluster. You can
create up to 16 clusters in the same VPC and secure them with the same firewall or firewall set.

![alt text](https://github.com/PaloAltoNetworks/aws-eks/blob/master/aws-eks.PNG "Logo Title Text 1")



## History

Version 1.0 - Aug 2019

The initial release of version 1.0 is provided as a community supported, i.e. best effort, release. You can consider this as an open beta to introduce new features and collect feedback for improving the generally available release that will be officially supported.