# Exercise 1 - Project Setup

In this exercise, we will create a Project. Projects are the key entities to facilitate SAP implementations. 

Projects can be equipped with project templates to best support different kind of implementations e.g. SAP S/4HANA Cloud, SAP SuccessFactors, or Intelligent Enterprise Suite focussed implementations. 
Projects also provide a time boxing and defines the teams and the concrete persons doing the project work.

You can now proceed with the exercise by reading the steps below. In case you find issues, you can look at the [recorded demo](https://wpb101101.hana.ondemand.com/wpb/pub/wa/index.html?library=library.txt&show=project!PR_459999E6D5BD26B2).

## Select Project Template and Define Timeboxes/Sprints
> We will begin many of the exercises from the Fiori launchpad. When you are within any application , you can click on the SAP Logo to return to Fiori Launchpad

1. Click Projects.
<br> ![](2021-11-11-15-00-33.png)

2.	Create Your Project
<br> ![](2021-11-11-15-04-38.png)
<br> (1) Click "Create".
<br> (2) Enter a project name. Please follow naming convention using current date, underscore, and a free text project name \<YYYYMMDD\>_\<Your Project Name\>.
<br> (3) Select "SAP S/4HANA, private edition (new implementation)" as template.
<br> (4) Click "Save".

3. Define Timeboxing
<br> In this Step you define the different timelines of Phases, Sprints or Milestones.
<br> ![](2021-11-11-15-15-26.png)
<br> (1) Click on the Timebox Tab
<br> (2) Enter planned dates for your phases. You do not need to enter dates of all the phases. you can as an example enter dates only for Prepare phase, Explore phase and Realize phase.
<br> ![](2021-11-11-15-19-41.png)
<br> (1) Start creating some sprints for your Project.
<br> (2) We recommend you that you create Sprints without overlapping dates.
<br> (3) You can notice that system already creates three milestones for you. You can populate dates for the milestones Kickoff and Planned Go Live.
<br> (3) Make sure you save the Project.

## Create Teams and Assign Persons

> **CAUTION**: This is not a productive SAP Cloud ALM environment. We are here in a shared demo environment and personal information can be seen by others. Please do **not** enter any personal data e.g. E-Mail adresses. Thank You!

1. Create Team and Assign Persons
<br> A Project can have multiple teams. Each team has multiple roles, users can be assigned to one or more roles or one or more teams. In order to onboard a new team member, the user needs to be entered here. This user has to be known to the Identity Provider (productive IAS) connected to SAP Cloud ALM, so that the user can be invited via eMail to the project. The team is displayed per Project, to edit it you need to navigate to the Teams tab under "Manage Projects" and select “edit”.
<br> ![](2021-11-11-15-28-24.png)
<br> (1)Team is shown only in display mode within a Project. Click "Manage Teams" to navigate to team maintenance UI

2. Maintain Team 
<br> In this UI you can edit details of the current team, or click Create in the left Panel to create a new Team. In this exercise only one Team is sufficient.
<br> ![](2021-11-11-15-31-30.png)
<br> (1) Click to change the Team Name.
<br> (2) Enter a team desciption.
<br> (3) Note that Project lead is assigned.
<br> (4) Click "Save" to save the changes.

## Summary

You've now setup your project.

Continue to - [Exercise 2 - Document Custom Processes](../ex2/)
