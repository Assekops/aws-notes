![AWS Networking](./diagrams/Multi%20tiew%20web%20application.png)

This example shows client over the internet interacting with the website hosted in Amazon EC2 in a public subnet of VPC. It is accessible to the anyone outside the company network. The appliation and processing code is stored in EC2 instance in provate subnet.

On premises users can access the VPC using virtual private network or VPN. If the website is meant to be accessed only company employees(e.g employee portal), even the presentation layer will be in a private subnet.
