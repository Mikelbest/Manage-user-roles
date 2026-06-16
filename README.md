# Manage-user-roles
Scenario: Your company recently hired a new employee who will perform duties as an application administrator. You must create a new user and assign the appropriate role.
Exercise - Create a new user and test their application admin rights
Open Microsoft Edge or any accepted browser and navigate to the Microsoft Entra admin center at https://entra.microsoft.com. or through the Microsoft office 365 site, admin.microsoft.com, Sign in using a Global Administrator or as a User Administrator.
Note: You may be prompted to complete Multi-Factor Authentication (MFA) during sign-in. Follow the prompts to configure or verify your authentication method before continuing.
In the left navigation menu, under Entra ID, select Users.
On the Users page, select All users, select + New user, and then select Create new user.
Create a user name called ChrisG with Display name Chris Green
<img width="1344" height="640" alt="image" src="https://github.com/user-attachments/assets/b71d5ce3-e67e-4687-aefb-35d4d97a7b62" />
Ensure the Auto-generate password option is marked, Copy the user name and the generated password to a location so you can access them in the next task. You will have to change the password upon first login to this account.
Select Review + Create. Then select Create on the review screen. The user is now created and registered to your organization.
Task - Login and try to create an app
Launch a new InPrivate or Incognito browser window and open Microsoft Entra admin center at https://entra.microsoft.com and sign in as Chris Green using the email from the user name created and the auto-generated password from the account creation.
Note: You may be prompted to complete Multi-Factor Authentication (MFA) during sign-in. Follow the prompts to configure or verify your authentication method before continuing.
You will be prompted to Update your password, in the space for current password, provide your auto-generated password, in the space for New Password, enter a unique and secure password, then confirm the password by inputing the same password, and you will be signed in. 
<img width="1336" height="639" alt="image" src="https://github.com/user-attachments/assets/376b642f-cb48-4634-9798-02c4f095e1d1" />
In the search box at the top of the page, search for Enterprise applications, and then select it from the results. Select + New application, and notice that + Create your own application is unavailable.
Exercise - Assign the application admin role and create an app. 
If you are not already logged in as an Administrator role, open the Microsoft Entra admin center and log in. In the left navigation menu, under Entra ID, select Users. Select All users under the Manage section of the menu. Select Chris Green account.Choose Assigned roles from the Manage menu. Select + Add assignments. Select Application administrator role from the dropdown. Select the Next button. Select the Active value for Assignment Type. You can enter a write up like a sentence for justification, revealing why you're assigning the role, and then Assign.
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/a40b5b8e-83ab-4da3-b303-c9f08129e322" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/199b6e9e-0756-42e1-8a11-82aa50f4ffa1" />
Note: If the lab environment has already activated Microsoft Entra ID Premium P2, Privileged Identity Management (PIM) will be enabled and you will need to select Next and assign a Permanent role to this user.
Task - Check application permissions
Launch a new InPrivate browser window. Open the Microsoft Entra admin center at https://entra.microsoft.com and sign in as Chris Green
In the search box at the top of the page, search for Enterprise applications, and then select it from the results. Select + New application. Notice that Create your own application is now available and no longer grayed out. Select + Create your own application. Notice that the Create button is now available at the bottom of the pane.
Note: After the Application Administrator role is assigned, this role now has the ability to add applications to the tenant. 
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/3183ad2e-ecf7-4aed-bb35-536aaa83533a" />
Exercise summary - In this exercise, we assigned the Application Administrator role to the user and verified that they could now create enterprise applications. This exercise showed how directory roles grant scoped administrative permissions.

