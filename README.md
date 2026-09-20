Oracle Pluggable Database Management – Assignment II

Student: Diane UMUTONIWASE

Student ID: 29787

Group: I

Course: Database Development with PL/SQL (INSY 8311)

Oracle Version: Oracle Database 21c Enterprise Edition 21.3.0.0

Operating System: Microsoft Windows 64-bit


1. Introduction

This assignment was about working with Oracle Pluggable Databases. I worked on creating and managing a PDB, creating and deleting a temporary PDB, managing a user inside the PDB, and using Oracle Enterprise Manager Database Express.


2. Oracle Environment

I used Oracle Database 21c Enterprise Edition on a Windows 64-bit computer.

The container database is ORCL.

The PDB used for the assignment is DI_PDB_29787.

The user created for the assignment is DIANE_PLSQLAUCA_29787.

I also used Oracle Enterprise Manager Database Express to view and manage the database environment.


3. Task 1 – Create a New PDB

The PDB used for this assignment is DI_PDB_29787.

I checked that the PDB was open and working correctly. It was showing READ WRITE.

I also checked the user inside the PDB. The username is DIANE_PLSQLAUCA_29787, and the account status was OPEN.

This user will be used for future work inside the PDB.


4. Task 2 – Create and Delete a PDB

For this task, I created a temporary PDB called DI_TO_DELETE_PDB_29787.

After creating it, I checked that it was available and opened it successfully. The PDB showed READ WRITE.

After confirming that it was working, I closed it and deleted it completely using the DROP PLUGGABLE DATABASE command.

I then checked the list of PDBs again and confirmed that DI_TO_DELETE_PDB_29787 was no longer there.


5. Task 3 – Oracle Enterprise Manager

I accessed Oracle Enterprise Manager Database Express using the local Oracle EM address.

The address used was:

https://localhost:5503/em/shell

At first, I experienced an authorization popup when trying to log in through the browser. I checked the Oracle EM service from Command Prompt and confirmed that the login page was working.

After trying a clean browser session, I was able to access the Oracle Enterprise Manager dashboard.

The dashboard showed my Oracle environment, including DI_PDB_29787, and my username was visible on the page.


6. Challenges I Faced

One problem I faced was when I first tried to create the temporary PDB. Oracle returned an ORA-65016 error because the file name conversion had to be specified.

I checked the database file locations and then created the temporary PDB from PDB$SEED using FILE_NAME_CONVERT. This worked successfully.

I also had a problem with the Oracle Enterprise Manager browser login. An authorization popup kept appearing. I tested the EM Express address using Command Prompt and confirmed that the Oracle login page was available. After using a clean browser session, I successfully reached the dashboard.


7. Evidence

I included screenshots showing the work I completed.

The screenshots include the PDB and user information, the PDB creation, the temporary PDB verification, the PDB deletion, and the Oracle Enterprise Manager dashboard.

The evidence is organized in the following folders:

pdb_creation/
pdb_deletion/
oem_dashboard/
screenshots/


8. Integrity Statement

I confirm that the work and screenshots in this repository are from the Oracle environment I used for this assignment. I completed the practical tasks and documented the results myself.


9. Submission Details

Issues Encountered: Yes

PDB Name Created: DI_PDB_29787

Temporary PDB: DI_TO_DELETE_PDB_29787

Repository Name: oracle_pdb_ass_II_29787_Diane# oracle_pdb_ass_II_29787_Diane
