# User-Deactivation-in-Mendix.

### Description:
User Deactivation module is used for automatically deactivating the active users after a designated time interval. This module incorporates time and day based deactivation system for managing user accounts.

### Usage Scenario:
1. User Deactivation can be integrated into various applications, particularly in small team collaborations, to enable to functionality of deactivating users when required.
2. User Deactivation is the best practice when you develop Mendix applications.

### Features 
1.	Simple Steps for adding module to your app.
2.	Easy configuration steps.
3.	This module allows for setting a specific time for deactivating users.
4.	You can deactivate users after a specified duration, such as a certain number of days, weekly, monthly, and yearly.

### Limitations
1.	Large number of deactivated users may impact the overall size and performance of database.
2.	If any user wants to reactivate their account after being deactivated, then this process involves additional authentication and verification to Admin.

### Pre-requisites
1.	Mendix Studio Pro Version 9.12.4

## Screenshots 
1. Setting Scheduled event using minutes for deactivating.
![image](https://github.com/kadamshweta11/User-Deactivation-in-Mendix./assets/67953305/7032595a-3e7f-4bac-9c25-08df5a32a3dd)

### Step by Step Configuration.
1. Install User Deactivation from Marketplace.
2. Setup Security to Production level.
3. Add User_List_Overview Page to Navigation Tab.
4. Setup Interval type of Scheduled events in minutes or according to your requirements.
![image](https://github.com/kadamshweta11/User-Deactivation-in-Mendix./assets/67953305/08b12b1c-7e83-41c6-b306-aa6ddfe8ea2a)
5. Add a Log Out functionality to Navigation Tab.
6. Run your App.
7. Enter Number of Days and click Submit button.
![image](https://github.com/kadamshweta11/User-Deactivation-in-Mendix./assets/67953305/62dfc2a1-e287-448f-ae93-327c9f499fef)
8. Check your Console if it looks like this then User Deactivation is working successfully
![image](https://github.com/kadamshweta11/User-Deactivation-in-Mendix./assets/67953305/535920c1-5484-40e6-bae3-8eb458e816d0)
9. Now check your Browser or refresh your browser  and you will see the result like this below:
Before
![image](https://github.com/kadamshweta11/User-Deactivation-in-Mendix./assets/67953305/068d5ceb-fc26-425a-be8c-98bc0b95d2d4)
After
![image](https://github.com/kadamshweta11/User-Deactivation-in-Mendix./assets/67953305/67a3661d-0297-4026-b51a-b9bf775f6489)
10. Congratulations your Users are Deactivating Successfully









