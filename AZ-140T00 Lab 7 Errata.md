# AZ-140T00 Configuring and Operating Microsoft Azure Virtual Desktop Lab 7 Errata
## Lab 7 - Create and manage session host images ~90 Minutes
### Exercise 1: Create custom session host images by using image templates
Task 1: Register required resource providers <br>
Step 1: Type http://portal.azure.com
Step 2: In the CloudShell select No storage account needed > Your Subscription > Apply. When the last CMDLet runs you will need to hit enter before closing the cloud shell <br>

Task 3: Create a custom Azure role-based access control (RBAC) role <br>
Step 3: When the last line of the script pastes, you will need to hit enter <br>

Task 4: Set permissions on the host image provisioning-related resources <br>
Step 7: Inside of the () will be your subscription ID not the number in the lab
Step 8: Search for the account (name) you created in Task 2 Step 3 <br>

Task 6: Build a custom image <br>
Step 5: You may have to click see all images > search for DC2s_v3 (note remove standard when searching)  <br>

Task 7: Build a custom image <br>
Step 2: Build took over 45 minutes to finish - this is a good point to take a break - but be mindfull of the timer <br>

Task 8: Deploy session hosts by using a custom image <br>
### After Step 6 before step 7: Do the following: After the VNet creation has finished - navigate to the HP1-Subnet and clear the check box on Enable private subnet (no default outbound access)

Step 12: You may have to click see all images > search for DC2s_v3 (note remove standard when searching)  <br>

