# AWS-SG-NACL

## Overview

This project hands-on project aimed at understanding the fundamental components of AWS securty groups and Network Access Contol lists. It explains how secirity group controls inbound and oubound traffic to EC2 instances and how Network Access Control Lists regulates traffic at the subnet level. Through practical demonstrations and interactive excercises, we'll navigate the AWS management console to deploy and manage this critical components effectively.

## Work through

Currently, we cannot access our previously hosted website eventhough our apache2 server appears to be serving it and this is due to the security group setting

= Creating a new security group
LOcate the security group menu
![Locate security menu](./images/locating_the_security_menu.png)

- Fill all the secuirty group details
  Such as name , description, VPC
![Details](./images/details.png)

- Click on the add rule button for the inbound rule
- select HTTP under type and anywhere as source
- select All traffic under the outbound rule
- Click on the create security group
![Seeting the rules ](./images/All.png)

## Attaching the security group to the instance

- Click on the instance
- click on action and click security
- Click on Change security group
- Select the security group you mjust created
- Click add security group and save
![Sselect and save the security group](./images/select_the_security_group.png)
