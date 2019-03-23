# Invite the members to "Residents"
This Action Card & Flow would help you in adding the members as "subscribers" to Residents group.

With Office 365, the admin will have an option to create a sharepoint site. create a site and it will be available as https://<sitename>.sharepoint.com

- Create a [SharePoint list](https://support.office.com/en-us/article/Create-a-list-in-SharePoint-0D397414-D95F-41EB-ADDD-5E6EFF41B083) with name as "Residents"

 Add the below list of columns 
| Column Name | Data Type |
| --- | --- |
| Flat No | Single line of text |
| Member Name | Single line of text |
| Phone Number | Multiple lines of text |
| ResidentType | Single line of text |
| Invited By | Single line of text |
| Invited By PhoneNumber | Single line of text |

- Create a Action card 
    -  ![Step 1](Media/InviteMember/ActionCardForm.png)
    -  ![Step 2](Media/InviteMember/ActionCardQuestions.png)

- Login in to https://flow.microsoft.com and import the flow
    Download the package by clicking on the "flow Package" , While importing the package, choose the connections by authentication.
    -  [Flow Package](Media/InviteMember/InviteMember_20190319234734.zip)

