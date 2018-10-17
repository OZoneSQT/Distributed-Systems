## Assignments
This directory contains all the assignments for the class. The common project `RecordsManagment` holds everything that is not specific to the framework of the assignment since those components will be re-used through out.

**Number** | **Name** | **Status**
:---: | :--- | ---
1 | JavaRmi | Completed
2 | Corba | _WIP_

### Notes
##### Creating Java Files from a .idl
For each .idl file run `idlj -fall <file_name>` and correct package naming if you are not using the default package

##### Starting the CORABA ORB
Run the following command `start orbd -ORBInitialPort 1050`