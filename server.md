## Server Notes
To get our server up and running we need to get ahold of a name and adress and connect the name to the address... then you will need to secure it. 
Example:
```
cd desktop/Education/BYU/CS-260
nslookup byu.edu
Server:		10.8.0.19
Address:	10.8.0.19#53

Name:	byu.edu
Address: 128.187.16.184
```

Domain Name:  
[subdomain.]*secondary(root/sld).top(tld)
- react.simon.cs260.click

DNS Record Type:
- A/AAAA (at most AA in this class)
  - Address. Specific IP adresses. IPV4 and IPV6. 

***We need to buy a domain on Route53***

To create a server go to EC2 > **make sure you are in N. Virginia** > launch an instance > name and tags > enter in some value > Application and OS Images > Enter in "ami-018f3a022e128a6b2" > Instance Type > Select t3_nano > associate a key pair with this server by creating a new key pair > ***... rest of the steps are in the class discord notes.***  
