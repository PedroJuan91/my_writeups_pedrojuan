MS flow and Excel
In this guide, I will show you how to use office365 in sending bulk emails using Gmail stored in your excel file. In this tutorial, you must have basic knowledge in HTML ( optional ), purchase a subscription on MS office365, a Gmail account, and some basic knowledge in flow charts.


## BASIC CONFIGURATIONS


First, open your account at office365 in you're favorite browser. After you open your account, select the excel file you want to send email in bulk.
![image_starting](https://i.imgur.com/dAR55sL.png)

At the file, the file must be in the table which is shown in the figure given ( very important ). If the file is not yet set click here for how to set a table in MS Excel.
![image_excel_table](https://i.imgur.com/Co9WujS.png)

after you have set up basic configurations in MS Excel. At your account in office365 open your MS Flow application.
![image_flow_app](https://i.imgur.com/rbcowKz.jpg)
The following are the actions needed for your automation in gmail.
>[create flow](#create-flow)

>[update flow](#update-flow)

>[run flow](#run-flow)

Check other options you can do with your MS Flow and MS Excel.
> Add image at your flow.

> Add attachments at your flow.


----------------------------------------------
## Create flow

after you open your MS Flow in your browser. Follow these steps on how to create a flow with MS Excel.

> **click create flow**
![image_flow_create](https://i.imgur.com/Ny0yIH1.jpg)

> **click instant flow**
![image_click_instant_flow](https://i.imgur.com/qbSrsUt.jpg)

> **Write your Flow Name. Scroll below, choose "MS Excel for business; FOR A SELECTED ROW". And click *Create*.**
![image_edit_config_instant_flow](https://i.imgur.com/PPls9ei.jpg)

>**The system will redirect you on its logic path which starts on "for a selected row" using excel.**
![image_done_create_instance](https://i.imgur.com/9x0320f.jpg)

->**After redirects you to the logic path, add another action or step to your logic path, and search Gmail and click "send an email (v2)".**
![image_add_gmail_step](https://i.imgur.com/6RoNs9z.jpg)


:party: :party: You have now created your flow. Now let us update the data within the logic path to our desired action of the flow.

## Update Flow

Congratiolations!! :party: :party:
You have made your flow, but this flow is not yet complete. 

In creating our flow, you have made 2 actions. A trigger ( *a selected row @ excel* ) and action ( *send an email: v2 @ Gmail* ). Each action there are updates needed to be filled in to work properly.

> ### Select a row (trigger)
	divided in 2 parts

		* file location / path - file path is based on where did you store your data. MS flow only accepts data from the OneDrive application.

		* table name - at the file of the excel select the desired table name for your logic path (very important)
![image_about_selected_row](https://i.imgur.com/LkJRkP4.jpg)

> ### send an email: V2 (action)
	
	divided into 3 parts
		
		recipients - the recipients can be fetched at the table on the excel file you have selected using DYNAMICS ( a pop-up of data from the selected row excel action.)

		subject and body - the contents can also be fetched at the table selected in the previews action. In the body, you can use normal input data at the body or if you have basic knowledge of HTML you can change the design of the email by using HTML.

		attachments - further actions are needed to use the attachments. So I made another article to avoid confusion whereas we are just sending a simple email from the recipients of the excel file.
![image_in_updating_send_email](https://i.imgur.com/Q97cyYJ.jpg)

After we have updated the data of the flow, **click the save button** to save the logic flow in the MS Flow. 

And we have successfully done in updating the data of the logic flow. Now let's run it

--------------

## Run Flow

Now we have created our flow and manage to update each content of the logic flow. Now we can run the flow. To run the flow, manage these steps to successfully run the flow.

> **check the flow checker beside the logic flow and with the dashboard of the flow if there are errors shown on it.**


> after you have confirmed your flow is correct. Click Save the logic flow and after saving return to your excel file. At the excel file in the menu bar go to "insert" -> add-ins. After clicking add-in apps search for flow add add it to your excel file.
> After you have add flow in your excel file. Go to Data -> Flow ( at the last end of the menu ). In there you will be directed to a portal of the list of flows within the excel file. After, click the name of the flow you have recently created.
> At the table you will use for the flow, highlight the specific rows you want to use to send an email.
> At the portal for the MS Flow in MS Excel, after you have selected your recently created flow, click RUN.
> After the permissions/connectors done accepted, click RUN
> And confirm the execution of the flow, and wait for its flag for "successfully done".
CONGRATULATIONS :party: :party:
YOU HAVE SUCCESSFULLY MADE IT!

To do more other than sending an email like an email with attachments in MS Flow (link) or adding an image in the email using MS Flow (link).
