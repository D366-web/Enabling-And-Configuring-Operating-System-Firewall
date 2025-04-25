# Enabling-And-Configuring-Operating-System-Firewall
This project demonstrates the steps to enable and configure the operarting system firewall on Window. The goal of this project is to provide comprehensive guide on securing window by configuring the firewall to allow or block incoming and outgoing network traffic.

What is a Firewall?
A firewall is a system that is designed to prevent unauthorized access to entering a private network by filitering the information that comes in from the internet. 
The purpose of a firewall is to create a safety barrier between a private network and a public network.

Project Overview
In this project, i will walk through the process of:

1. Enabling the window operating system firewall to improve security
2. Configuring firewall rules
3. Allowing or blocking programs and applications. 


To get started, access your operating system’s firewall settings by following these steps:

1. Open the Settings menu, then navigate to the Window Security section and click on it.
<img src="./1.png" width="100%" height="auto">

2. Go to Window Security and check the Firewall & Network Protection settings to make sure the firewall is turned on.
 <img src="./2.png" width="100%" height="auto">
If it's not turned on, click the Enable or Turn On button.
 <img src="./3.png" width="100%" height="auto">
 
 Step 2: Configuring basic Firewall
 
 1. Go to the firewall settings and find Advanced Settings.
 <img src="./4.png" width="100%" height="auto">

 2. You'll see three types of network profiles: Public, Private, and Domain. Pick the one you want to change.

3.  Decide whether you want to block traffic coming in (incoming) or going out (outgoing).
 <img src="./5.png" width="100%" height="auto">
  
4.  On the right side, click New Rule.
 <img src="./10.png" width="100%" height="auto">
 
5. You can create a rule for a program, a specific port, a website address (HTTP), or make your own custom rule. Click on program
<img src="./6.png" width="100%" height="auto">
 
7. Next, choose which app you want the rule to apply to. For this example, Google Chrome is used as the web browser
<img src="./11.png" width="100%" height="auto">

8. When you get to the screen that asks what to do with the connection, choose Block the connection.
<img src="./8.png" width="100%" height="auto">

9. Click Next, then choose when the rule applies (Domain, Private, Public).
<img src="./9.png" width="100%" height="auto">

10. Give the rule a name (like "Block Google Chrome"), and click Finish.
<img src="./79.png" width="100%" height="auto">

Step 3: Testing the firewall rule
To ensure the firewall rule is working correctly, you can test it by attempting to access a service running on the blocked port. Follow these steps:  

1. Launch the browser for which you applied the rule in step 2.
2. If the firewall rule is configured correctly, you should receive an error message indicating that the connection was blocked.
<img src="./77.png" width="100%" height="auto">

Conclusion
This project demonstrated the process of enabling and configuring the built-in firewall on Window Operating System. It included locating the firewall settings, activating the firewall, and creating a rule to block a specific program. The steps followed highlight essential skills for managing network security and protecting digital environments from unauthorized access.
   

 





