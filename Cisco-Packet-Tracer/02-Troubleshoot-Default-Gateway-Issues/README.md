#  Troubleshoot Default Gateway Issues
----------------------------------------------------------

#  Objectives
Part 1: Verify Network Documentation and Isolate Problems
Part 2: Implement, Verify, and Document Solutions.
-----------------------------------------------------------

  #  Resources
-----------------------------------------------------------
Addresses Table


  ![Addresses Table](Images/01-Address-table.png)

Network connections


  ![Network connections](Images/02-Network-connections.png)
  
------------------------------------------------------------

  #  Background/ Scenario
For a device to communicate accross multiple networks, it must be configured with an IP address, subnet mask, and a default gateway. You will then verify the network documentation by testing en-to-end connectivity and troubleshooting issues.

--------------------------------------------------------------
#  Part 1: Verify Network Documentation and Isolate Problems
  #  Step 1: Verify the network documentation and isolate any problems
In this part I documented multiple connection tests between the devices listed on the Address Table, to ensure every device have the right configuration and is working properly.

![Tests Table](Images/03-Test-table.png)

I apply the "ping" command multiple times to check the connection from PC1 to the other devices on the network.

  #  Step 2: Determine an appropiate solution to the problem

On this time only the connection from PC1 to PC2 and connection from PC1 to PC4 failed, for PC1 to PC2 the problem was related to a wrong IP address for PC1.
So I update the IP information with the correct IP address according to the Addresses table information. 

  ![IP address updated PC1](Images/04-IP-address-PC1.png)

Also ping PC2 from PC1 to check the connection is now working properly

  ![Ping PC2 from PC1](Images/05-Ping-PC2.png)

For the connection issue from PC1 to PC4, I verify the PC4 IP configuration info and discovered the Default Gateway was completed incorrectly, so I update this info according to the info provided on the Adresses table.

  ![Solution PC4](Images/06-Solution-PC4.png)

Then I verified the connection between PC1 and PC4 to check the PC4 issue was solved successfully.

  ![Ping PC4 from PC1](Images/07-Ping-PC4.png)

As you can see the connection issue was fixed correctly.


#  What did I learn?

I practice how to identify different connection related issues as a wrong IP address or an incorrect Default Gateway and determine a solution to ensure a proper connection between every device on the network. Also, I learn how to document the process and compare how the network can change applying different configurations.
I also put in practice the following habilities:
-  Basic Troubleshooting
-  Connectivity Verification
-  IP address Configuration


  



  

  

