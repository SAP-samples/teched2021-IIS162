# Exercise 7 - Manage Deployments

In this exercise, we will manage the deployment of Transport Requests through the landscape. SAP Cloud ALM bundles Transport Requests into Features. Let's do this.
<br>
<br>You can now proceed with the exercise by reading the steps below. In case you find issues , you can look at the [recorded demo](https://wpb101101.hana.ondemand.com/wpb/pub/wa/index.html?library=library.txt&show=project!PR_9DDFE782732B9897).

## Create Feature

1. Enter Features
<br> ![](2021-11-12-10-53-56.png)
<br> (1) Click "Features".

2. Create Feature
<br> ![](2021-11-12-10-54-15.png)
<br> (1) Click "Create".

3. Specify Feature 
<br> ![](2021-11-12-10-54-32.png)
<br> (1) Enter "Determine Refund Configuration and Developments" as title.
<br> (2) Set Scope "Plant Berlin".
<br> (3) Set Workstream to "Application Design and Configuration".
<br> (4) Set Priority to "High".
<br> (5) Enter "Transport of Friendly Policy Configuration and Developments." as description.
<br> (6) Click "Save".  

## Assign Transports

1. Start Implementation
<br> ![](2021-11-12-10-54-46.png)
<br> (1) Click "Start Implementation".

> Please assign only one Transport Request to your Feature. This a courtesy to your fellow workshop participants to make sure everybody finds at least one Transport Request to assign.
2. Assign Transport Request
<br> ![](2021-11-12-10-55-01.png)
<br> (1) Click "Assign".

3. Find Transport Request
<br> ![](2021-11-12-10-55-18.png)
<br> (1) Search for Transport Requests containing string "IIS162".
<br> (2) Select **one** Transport Request.
<br> (3) Click "Save".

<br> A transport can only be assigned to one Feature. When you select a Transport Request it may already be assigned to a transport by a fellow workshop participant. In this case you would see the following error message:

<br> ![](2021-11-15-16-07-30.png)
<br> In this case please re-open the dialog and pick a different Transport Request.

## Release and Deploy Feature

1. Delpoy to Quality Assurance
<br> ![](2021-11-12-10-55-36.png)
<br> (1) Click "Deploy" to release Transport Request from **development** tenant/client to **test** tenant/client.

2. Refresh Transport Request Status
<br> ![](2021-11-12-10-55-50.png)
<br> (1) Click refresh icon and wait until the Transport Request arrived in the target tenant/client.

3. Approve for Production
<br> ![](2021-11-12-10-56-03.png)
<br> (1) Click "Approve for Deployments" after the Transport Request has beed successfully tested in the test tenant/client.

4. Deploy to Production
<br> ![](2021-11-12-10-56-14.png)
<br> (1) Click "Deploy" to release Transport Request from **test** tenant/client to **production** tenant/client.

5. Refresh Transport Request Status
<br> ![](2021-11-12-10-56-32.png)
<br> (1) Click refresh icon and wait until the Transport Request arrived in the target tenant/client.

6. Confirm Deployment
<br> ![](2021-11-12-10-56-46.png)
<br> (1) Click "Confirm Deployment" to confirm that the Transport Request reached the production tenant/client.

7. Open History
<br> ![](2021-11-12-10-56-58.png)
<br> (1) Click history icon.

## Review Deployment History

1. Review History
<br> ![](2021-11-12-10-57-12.png)
> Review Feature history to find out who deployed what, when, and to what target tenant/client.
 
## Summary

You've now deployed configurations and developments. Well, the hard work is done. Or have we missed something? Let's check...

Continue to [Exercise 8 - Project Overview and Traceability](../ex8/README.md)
