# AZ-140T00 Configuring and Operating Microsoft Azure Virtual Desktop Lab 4 Errata

# Lab 4 - Connect to session hosts (Entra ID) ~20 Minutes

## Lab Setup

### Note the role assignments created in Lab 1 have expired you will need to change the assignment

Step 1: From the lab computer, in the web browser displaying the Azure portal, search for and select Resource groups and, on the Resource groups page, select az140-21e-RG <br>
Step 2: On the az140-21e-RG page, in the vertical navigation menu, select Access control (IAM) <br>
Step 3: Click Role Assignments <br>
Step 4: Search for your AVd-DAG group identified in Lab 1 <br>
Step 5: Click on Eligible time-bound under state <br>
Step 6: Select Active and Permanant, click Save <br>
Step 7: Search for your AVd-RemoteApp group identified in Lab 1 <br>
Step 8: Click on Eligible time-bound under state <br>
Step 9: Select Active and Permanant, click Save <br>

### Exercise 1: Validate the functionality of Microsoft Entra joined Azure Virtual Desktop session hosts by connecting to them from a Windows 11 client <br>

Task 2B (Optional): Install Microsoft Windows App on a Windows 11 computer <br>
Step 1: Launch the Microsoft Store <br>
Step 2: Search for RDP > Select Windows App > Select Get After installation close the Microsoft Store > continue to task 3 <br>

Task 3B (Optional): Subscribe to a Azure Virtual Desktop workspace using Windows App <br>
Step 1: On the lab computer, switch to the Windows App, select sign in with the credentials of the User1 Entra ID user account which you can locate on the Resources tab in the right pane of the lab interface window <br>
Step 8: On the Windows App, click Connect <br>
Step 12: Back in the Windows App Click on the US in the upper right corner select sign-out <br>
Step 13: In the Windows App, Pick Use another account, sign in with the credentials of the second Entra ID user account which you can locate on the Resources tab in the right pane of the lab interface window <br>
