# Ex-12-Automate-an-unattended-Robot-using-Orchestrator

~~~
Name : W Allen Johnston Ozario
Reg.No : 21222411004
~~~

## Aim
To automate and execute an unattended Robot in UiPath Orchestrator by publishing a project from UiPath Studio, creating necessary assets and triggers, and running the process remotely.

## Materials Required
UiPath Studio (connected to Orchestrator)

UiPath Orchestrator Account (Cloud or Enterprise)

UiPath Assistant

Robot provisioned and licensed in Orchestrator

Stable internet connection

## Procedure
Step 1: Create and Publish a Project
Open UiPath Studio and create a sample project (e.g., a Message Box or any automation).
Save the project and click "Publish" to upload it to Orchestrator (Tenant Processes Feed).

Step 2: Log in to UiPath Orchestrator

Go to https://cloud.uipath.com and log in.
Choose your Orchestrator tenant.

Step 3: Provision Robot and Machine
Go to Tenant > Machines: Add a Standard Machine with the same name as your device (check in Studio via Help > License Details).
Under Tenant > Folders > Manage Access, ensure your user is assigned with proper roles (e.g., Robot role).
Go to Tenant > Robots and create a Unattended Robot:
Link it to the correct machine and user.
Assign it to your folder.

Step 4: Create Process in Orchestrator

In Automation > Processes, click Add Process.
Select the published package from the dropdown.
Choose version, folder, and display name.
Click Create.

Step 5: Create Trigger to Schedule the Robot
Go to Automation > Triggers.
Click Add Trigger:
Select your process.
Set Trigger Type to Time.
Choose the time, frequency (Once, Daily, etc.).
Click Create.

Step 6: Monitor Execution
In Jobs, you can monitor the status (Pending, Running, Success, Faulted).
View logs, time stamps, and robot execution details.

## OUTPUT:
A process, published from UiPath Studio, is executed automatically without manual intervention via an unattended robot in Orchestrator.

## Result
The automation process was successfully published, triggered, and executed as an unattended job using UiPath Orchestrator. This setup ensures automation can run without human presence at scheduled times.
