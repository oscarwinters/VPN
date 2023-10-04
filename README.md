![image](https://github.com/oscarwinters/VPN/assets/146681785/73ed9b6a-3dc8-4603-9466-f9d40f83c503)


 
<h1>On-Virtual Private Network Setup And Usage (ProtonVPN)</h1>
This tutorial outlines the implementation of a virtual private network within ProtonVpn.<br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- What is my IP address services
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1.) Browse to the public website @(whatismyipaddress.com) to get your current IP address and notete it
![2023-10-03 (16)](https://github.com/oscarwinters/VPN/assets/146681785/1bd79d85-5c88-420b-b9a9-c67ad9ca373c)

- Step 2.) Create a VM in Azure in a different country from your personal, then connect it to Remote Desktop protocol
![2023-10-03 (9)](https://github.com/oscarwinters/VPN/assets/146681785/626f7ec7-3130-46fe-baba-7a3cee3b0749)
![2023-10-03 (2)](https://github.com/oscarwinters/VPN/assets/146681785/a598dc8c-1ea8-4b2f-b000-62abde5a4175)


- Step 3.) Once connect to our Azure VM browse back to(whatismyipaddress.com) site in notete the IP address and location in text files 

![image](https://github.com/oscarwinters/VPN/assets/146681785/9648dca9-6034-45a9-bbf4-059602f54f54)


- Step 4.) Sign up for the free version of proton VPN in download the "Windows vpn client" and install it
![image](https://github.com/oscarwinters/VPN/assets/146681785/41c92950-3b33-420c-8bc3-9b56714fe160)

![image](https://github.com/oscarwinters/VPN/assets/146681785/24f4682d-b9f7-4766-b4d6-e75327a8adca)

- step 5.) From within the VM you will connect to a portion vpn server in free trail choice (somewhere in the U.S), go back to the site(whatismyipaddress.com) inside your VM to notete the new IP adress and loction to notice the dfferent IP inside of your Azule VM to understand the fundamentals on how a VPN works and can be created in a VM  
![2023-10-03 (11)](https://github.com/oscarwinters/VPN/assets/146681785/e2acfcc9-f4ef-4ad8-bb00-7c53d3385c5f)
![image](https://github.com/oscarwinters/VPN/assets/146681785/fd2e9541-f591-4ccb-a2b8-dafff9fdebcd)

With this cousre you should have a clear understanding on whata VPN is and how you can creat one using a VM, and here are a few different types of VPN's to be known of. 

Here are a few different VPN to be aware of 👇

1.) Anoymity: when you are connected to a VPN server, and the server actual IP address is hidden, and the server's IP address is used instead. The helps to anonymize your online activities, making it more chanllenging for website and online services to track anyone loction and also their identity. 

2.) Security: Vpns are usually used to more advance the security of a someone’s public Wi-Fi networks, if they connect to a public Wi-Fi hotspot using a vpn, their data is encrypted, minimizing the satay being intercepted by malicious users on the same network 

3.) Privacy: VPNs is mostly used to protect your online privacy it prevents your internet service provider also known as (ISP), from your online activities to be monitored, it also helps prevent from malicious users that selling your browsing history to advertisers 
