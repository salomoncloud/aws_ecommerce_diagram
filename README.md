# aws_ecommerce_diagram
creating an aws diagram for a highly available fault tolerant e-commerce website
-
![image](https://github.com/salomoncloud/aws_ecommerce_diagram/assets/158000174/b0010e10-6321-41b0-aec8-dc283b92e3e2)
Sources used as references:
https://eyal-estrin.medium.com/using-the-cloud-to-build-multi-region-architecture-74db2a982186

https://cloudavenue.in/cloudavenue-architecture-center-2/e-commerce-solution-on-azure/

https://clutch.co/resources/how-to-move-your-e-commerce-website-to-amazon-web-services

https://www.linkedin.com/pulse/aws-infrastructure-support-highly-loaded-ecommerce-alexander-abgaryan/

https://docs.aws.amazon.com/global-accelerator/latest/dg/getting-started-standard.html

https://aws.amazon.com/containers/


explanation:
The task at hand when creating an e-commerce website is high availability, fault tolerance, secure and accurate transaction, and high speed as well. 
To do all this, I started by planning a multi-regional setup, as well as a multi-AZ setup within those regions. 
I than decided to implement a WAF to enhance security and protection against DDoS to ensure uptime as well as Global accelerator that would help route traffic for clients wherever they are in the world to have the best and fastest service. And this last point is the reason why I chose AWS, as they have the largest footprint in the world when it comes to data centers and POP's. 
