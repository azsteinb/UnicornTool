# Unicorn Tool
Made by Aaron Steinberg for the University of California Santa Cruz ITS Team
## Requirements
+ Python
+ Google API Key
+ Google Admin Permissions
## Purpose
Large organizations that use Google Workspaces tend to have certain users that could be designated as power users. These users can push the limits of the software provided by a large organization. In terms of Google Workspaces, power users may create "Shared Drives" that use 10's or 100's of TB of cloud storage. Power users might be finding loop holes in storage policy to store more. Power users tend to continue to use their account after they leave the organization, but not always. Sometimes, power users leave behind swaths of data that are not caught in standard, manual and/or automatic, off-boarding processes. This applies to normal users too. This internal software, "Unicorn Tool," allows administrators to query their organizations for leftover data and resources still hogging organization resources. It also allows administrators to act as a probate judge in where this data goes. The administrator can elect for the data to be deleted, inherited by subordinates of former employees, transferred to different teams, and more. Administrators can also setup automatic jobs to happen within their workspace, such as a "janitorial" service for data technically owned by previous employees or members of the organization.
## Use Cases
+ Querying for Drives, Calendars, and other data owned by inactive employees
+ Querying for Shared Drives that are abusing storage limits
+ Other custom queries
+ A number of actions that can be taken on a single or batch of objects such as Drives, Calendars, etc