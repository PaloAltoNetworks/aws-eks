Palo Alto Networks now provides templates to help you deploy an Elastic Kubernetes Service (EKS) Cluster in an AWS VPC. The Panorama plugin for Amazon EKS secures inbound traffic to Kubernetes clusters, and provides outbound monitoring for traffic exiting the cluster. The solution works in conjunction with [AWS AutoScale Groups](https://docs.aws.amazon.com/autoscaling/ec2/userguide/AutoScalingGroup.html) which allows you to deploy an auto-scaling tier of VM-Series firewalls using several native AWS services. The template allows you to deploy the EKS cluster in one of the spoke VPC's in the auto scaling solution.

## Requirements   
- The minimum Panorama software version is 9.0.3.
- EKS Plugin on Panorama—version 2.0.0.
- VM-Series firewalls PAN-OS version 8.1 and later, or version 9.0.3 and later.

![alt text](https://github.com/PaloAltoNetworks/aws-eks/blob/master/aws-eks.PNG "Logo Title Text 1")

## Deployment Guide      
The deployment guide can be found 
[HERE](https://github.com/PaloAltoNetworks/aws-eks/blob/master/Secure-Kubernetes-services-in-EKS-clusters.pdf)  

## History  

Version 1.0 - Sept 2019 Beta

## Support Policy  
***Community-Supported***      
This CFT is released under an as-is, best effort, support policy. These scripts should be seen as community supported and Palo Alto Networks will contribute our expertise as and when possible. ***We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options.*** The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself. Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.

