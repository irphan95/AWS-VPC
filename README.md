# AWS-VPC
- #### Click on create vpc option.
![step1](https://user-images.githubusercontent.com/103019032/173233007-073032b4-4f2d-4326-bfb4-d01cd59292e6.PNG)
- #### After clicking on create vpc,now can create vpc,give name of vpc its optional,you can give or not,but if you give the name of vpc you can easily identify the vpc,after give the name of vpc,give the range of vpc.An IPv4 address consists of 32 bits.
- #### a) /32 in CIDR x.x.x.x/32 means use all 32 bits to form a range of addresses. In this case just one IP address is possible.
- #### b) /24 in CIDR x.x.x.0/24 means fix the first 24 bits and use last 8 bits to form a range of addresses. In this case, there can be 2^8 IP addresses i.e. from x.x.x.0 to x.x.x.255.
- #### c) /16 in CIDR x.x.0.0/16 means fix the first 16 bits and use the last 16 bits to form a range of addresses. In this case, there can be 2^16 IP addresses i.e. from x.x.0.0 to x.x.255.255.
- #### d) /8 in CIDR x.0.0.0/8 means fix the first 8 bits and use the last 24 bits to form a range of addresses. In this case, there can be 2^24 IP addresses i.e. from x.0.0.0 to x.255.255.255.
- #### e) /0 in CIDR 0.0.0.0/0 means fix the first 0 bits and use the last 32 bits to form a range of addresses. In this case, all the possible IP addresses are included in the range.
![step2](https://user-images.githubusercontent.com/103019032/173233017-beba8d17-0450-4801-b4df-eeb3076d8882.PNG)
- #### You can see successfully created vpc,you can also see the details of vpc,i.e ip range, route table etc.
![step3](https://user-images.githubusercontent.com/103019032/173233024-329b8a09-c9e7-40fc-a3c6-2f0a51cd8e69.PNG)
- #### In the above vpc details screenshot see the details of route table,I creaated vpc-test route table.
![step4](https://user-images.githubusercontent.com/103019032/173233026-9f3c7e23-37bc-442f-8ea0-eca3f1ef0f9f.PNG)
- #### In the next step, i will create subnet,i will make two public and private subnet,and click on the create subnet option.
![step5](https://user-images.githubusercontent.com/103019032/173233035-f0e06769-c977-4b51-be85-c48f2bcf7735.PNG)
- #### In this step, i gave the name of subnet,and choose availability zone,give the range of ip adress,click on create subnet.
![step6](https://user-images.githubusercontent.com/103019032/173233044-c0f08cdc-4685-418d-9274-00e321e20029.PNG)
- #### In this step i have successfully created on subnet,i.e name of public subnet 1a.
![step7](https://user-images.githubusercontent.com/103019032/173233050-575932f6-6419-4632-9171-83119f6d6f64.PNG)
- #### Now i'm going to create second subnet,i.e name of public subnet 2a,and choose availability zone,give the range of ip adress,click on create subnet.
![step8](https://user-images.githubusercontent.com/103019032/173233053-63d70570-af9f-4f0a-a682-dca7f4369d3b.PNG)
- #### In this step i have successfully created on subnet,i.e name is public subnet 1a and 2b
![step9](https://user-images.githubusercontent.com/103019032/173233058-35096c36-87b9-42e7-9cda-67616ca7b637.PNG)
- #### In this step create the private subnet i.e name is private subnet 1a ,choose availability zone,give the range of ip adress,click on create subnet.
![step10](https://user-images.githubusercontent.com/103019032/173233065-3ffdf384-c40f-44d2-9dc7-b468719b51c5.PNG)
- #### In this step i have successfully created on subnet,i.e name is private subnet 1a.
![step11](https://user-images.githubusercontent.com/103019032/173233068-c920d419-593b-4954-8a7c-dc59c2430d8f.PNG)
- #### Now i'm going to create second subnet,i.e name of private subnet 2a,and choose availability zone,give the range of ip adress,click on create subnet.
![step12](https://user-images.githubusercontent.com/103019032/173233072-6d522ef0-b971-4d10-9e7c-947a4e0c665f.PNG)
- #### In this step i have successfully created on subnet,i.e name is private subnet 2a.
![step13](https://user-images.githubusercontent.com/103019032/173233076-89825d73-7274-43d8-a200-9dd316983b90.PNG)
- #### Go to route table option,click on subnet association.
![step14](https://user-images.githubusercontent.com/103019032/173233078-3f10bb30-22ef-455c-b03d-8c18cfafe713.PNG)
- #### After go to the route table option,you can see there are four subnet,two for public subnet,and other is private subnet.
![step15](https://user-images.githubusercontent.com/103019032/173233084-c5bde0d3-1cf4-4d7c-a9a1-021503984181.PNG)
- #### In this step select public subnet option,and click on save association.
![step16](https://user-images.githubusercontent.com/103019032/173233089-f6099f19-87eb-4b5b-999e-5a74d8c93231.PNG)
- #### After this step,successfully updated subnet,and show two subnet in vpc test-vpc-rt name of route table.
![step18](https://user-images.githubusercontent.com/103019032/173233093-6d61d878-f109-46af-9f83-27c75e697f4d.PNG)
- #### In this step,i will create route table for private subnet.
![step19](https://user-images.githubusercontent.com/103019032/173233100-2775ae90-b54b-4887-a3cb-93552c85722a.PNG)
- #### Now successfully created route table.
![step20](https://user-images.githubusercontent.com/103019032/173233102-61f0a62b-445c-4317-ba88-f5d989dcdf65.PNG)
- #### In this step,we see the details of subnet.
![step21](https://user-images.githubusercontent.com/103019032/173233105-f0fbae8f-f55e-4751-93d6-c959be60dab4.PNG)
- #### In this step select private subnet option,and click on save association.
![step22](https://user-images.githubusercontent.com/103019032/173233106-dd7f7018-16bd-4868-b6ed-4ba293879357.PNG)
- #### After this step,successfully updated subnet,and show two subnet in vpc test-vpc-privateRt name of route table.
![step23](https://user-images.githubusercontent.com/103019032/173233107-27a005da-30a2-4f6c-abf5-693e43c600e2.PNG)
- #### Now i will create the internet gatway for public ip.click on the create internet gateway
![step24](https://user-images.githubusercontent.com/103019032/173233114-b6751d72-8adb-4bc1-871f-fcfa8f6c6fe9.PNG)
- #### After clicking on ineternet gateway,give the name of internet gateway,and click on internet gateway
![step25](https://user-images.githubusercontent.com/103019032/173233119-9e50e26a-09c4-4d1c-9df8-a874437ac4f9.PNG)
- #### In this step, successfully craeted internet gateway,and show the details of internet gateway.
![step26](https://user-images.githubusercontent.com/103019032/173233121-45369d72-9955-4353-81e1-6f68fcf110cc.PNG)
- #### In this step,go to the route table,and select vpcpublicRT for public ip,and click on edit route table.
![step27](https://user-images.githubusercontent.com/103019032/173233125-8147f130-6263-4aba-a55e-cd5934c80d84.PNG)

![step28](https://user-images.githubusercontent.com/103019032/173233129-f827e2cd-47d7-45c7-9933-59c8f4849152.PNG)
![step29](https://user-images.githubusercontent.com/103019032/173233132-e7827ca8-1d77-4e73-971a-91c8a2ea0c70.PNG)
![step30](https://user-images.githubusercontent.com/103019032/173233140-c6ba5cad-2f8d-43c8-bee8-8c5743fc8b70.PNG)
![step31](https://user-images.githubusercontent.com/103019032/173233142-ffd86aec-f61c-48d8-8e49-f6d9658d92be.PNG)
![step32](https://user-images.githubusercontent.com/103019032/173233147-c69806a5-bcb4-46d6-b646-30b2388bc285.PNG)
![step33](https://user-images.githubusercontent.com/103019032/173233152-bc7baca6-6ea2-4c25-b956-9cde11c1be87.PNG)
