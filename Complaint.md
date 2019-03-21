# Compliant for "Residents"
This Action Card & Flow would help residents to raise a complaint.

When a complaint is raised by the resident, The system should send acknowledgement with complaint number to resident and post an action card to "Operations" group. Operations team can also take actions.

- Step 1: Create the [SharePoint list](https://support.office.com/en-us/article/Create-a-list-in-SharePoint-0D397414-D95F-41EB-ADDD-5E6EFF41B083)
    - List Name: "Complaints"
    - List of columns

| Column Name | Data Type |
| --- | --- |
| Flat No | Single line of text |
| Problem Type | Single line of text |
| Problem Description | Multiple lines of text |
| Photo of ticket | Single line of text |
| Comments| Single line of text |
| Feedback PhoneNumber | Single line of text |
| User | Single line of text |
| Status | Choice "Submitted, Re-opened, Closed, Working", default is "submitted" |
| Comments | Single line of text |
| Reopen Comments | Multiple lines of text |
| phnumber | Single line of text |


- Create a Action card 
    -  Step 1: ![Step 1](Media/Complaint/ActionCardForm.png)
    -  Step 2: ![Step 2](Media/Complaint/ActionCardQuestions.png)
    -  Import two more actions cards
        - Step 3: Action Card used by operations team to update the status.
        [Update from operations](Media/Complaint/Operations.ComplaintUpdate.zip)
        - Step 4: Action Card used by the residents to reopen the ticket. [Reopen ticket by residents](Media/Complaint/Complaint.Resident.Status.zip)
    
    Download the package by clicking on different flow packages, While importing the package, choose the connections by authentication.
    -  Step 4: [Complaint Flow](Media/Complaint/RaiseComplaint_20190320004523.zip) (Custom Action card is posted to get update from operations team.)
    -  Step 5: [Update from Operations](Media/Complaint/ComplaintOperationsUpdate_20190320032956.zip) (Operations team would update the status and comments would be added.)
    -  Step 5: [Reopen ticket by Residents](Media/Complaint/ComplaintReopenResidents_20190320033112.zip) (Residents would have a option to reopen the ticket with comments.)


- Login in to https://flow.microsoft.com and import the flow.