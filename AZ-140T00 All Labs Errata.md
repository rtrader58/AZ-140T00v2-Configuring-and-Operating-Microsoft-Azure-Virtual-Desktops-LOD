# AZ-140T00 Configuring and Operating Microsoft Azure Virtual Desktop All Labs Errata

# Lab 1 – Deploy host pools and session hosts by using the Azure portal (Entra ID) ~60 Minutes

### Exercise 1: Implement an Azure Virtual Desktop environment using Microsoft Entra joined session hosts 

Task 1: Prepare the Azure subscription for deployment of an Azure Virtual Desktop host pool <br>
Step 2: Select  No Mount storage account needed > Select Subscription in dropdown > Click Apply <br>
Step 13: Search for User1 that is in your resources dropdown <br>
Step 16: Copy the name of the Group into Notepad <br>
Step 17: Search for User2 that is in your resources dropdown <br>
Step 20: Copy the name of the Group into Notepad <br>

Task 2: Deploy an Azure Virtual Desktop host pool <br>
Step 3: Student password, use the password for User-1 add additional characters to make it 12 characters in length if needed (I added 123) <br>

# Lab 2 - Manage host pools and session hosts by using the Azure portal (Entra ID) ~30 Minutes

### Exercise 1: Manage an Azure Virtual Desktop environment containing Microsoft Entra joined session hosts

Task 3: Assign the required RBAC role to an Azure Virtual Desktop service principal <br>
Step 2: Only paste PowerShell script under the work powershell <br>

# Lab 3 - Implement monitoring by using Azure Virtual Desktop Insights ~25 Minutes

### Exercise 1: Implement monitoring of an Azure Virtual Desktop environment

Task 1: Register the Azure subscription with the Microsoft.Insights resource provider <br>
Step 3: Continue to refresh screen until status shows registered <br>

Task 3: Set up the Virtual Desktop Insights configuration workbook <br>
Step 5:  Click Configure workspace <br>
Step 13: Select Session host data settings <br>

# Lab 4 - Connect to session hosts (Entra ID) ~20 Minutes

### Exercise 1: Validate the functionality of Microsoft Entra joined Azure Virtual Desktop session hosts by connecting to them from a Windows 11 client

Skip Task 1: Adjust RDP properties of the Azure Virtual Desktop host pool (Breaks the abilty to log into the AVD as User1 and User2 <br>

# Lab 5 - Implement and monitor autoscaling of session hosts ~45 Minutes

### Exercise 1: Implement Azure Virtual Desktop autoscale scaling plans

Task 1: Assign the required RBAC role to an Azure Virtual Desktop service principal <br>
Step 3: Only paste PowerShell script under the work powershell <br>

# Lab 6 - Implement Azure Private Link for Azure Virtual Desktop ~60 Minutes

### Exercise 1: Implement Azure Private Link for Azure Virtual Desktop

Task 5: Implement a private endpoint for initial feed discovery <br>
Step 13: If the Virtual desktops are deallocated - start the desktop - before restarting <br>

Task 6: Validate the private endpoint functionality <br>
Step 18: Select My IP as Source <br>
Step 19: Select IP Addresses as Source > Verify that Source IP Address matches your address <br>

## Lab 7 - Create and manage session host images ~90 Minutes

### Exercise 1: Create custom session host images by using image templates

Task 1: Create a user-assigned managed identity <br>
Step 4: Replace the (Random) in the Name with your initials <br>

Task 2: Create a custom Azure role-based access control (RBAC) role <br>
Step 3: Paste in Notepad and Replace (Random) with Name of the Managed Identity created in Task 1 Step 4 > Paste into Cloudshell <br>

Task 6: Build a custom image <br>
Step 2:  Build took a total of 45 minutes to build <br>



