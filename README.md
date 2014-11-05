mHealthDataInterface
====================

Module mHealthDataInterface will provide Patient's and Health Worker's details based on Name, ID or Locality.
These details will be exposed as web services hence, any other application based on any platform can consume these web services and
use the Patient's and Health Worker's details according to their needs.


New module mHealthDataInterface has been developed as a separate external module to MOTECH core platform, similar to other modules like Commcare, OpenMRS etc.
Main purpose of this module is “To fetch the details of patients and health workers from MOTECH and expose the required web service APIs providing these data to consumers (developers) for further usage.”

It provides various APIs, through which details of patients can be fetched based on their locality, name or ID. Also the details regarding encounters that happened with health workers can be fetched.
This data is exposed through Spring-based web service APIs which can be consumed by any application further.
Additional application that has been used with MOTECH core platform is OpenMRS local running instance for getting access to the Patient and Health Worker database. 
Open MRS module of MOTECH also fetches information from this database. OpenMRS exposes some REST based web services through which the records from the OpenMRS database can be fetched and used.
The services and the database of OpenMRS can be leveraged further to add new APIs to our new module mHealthDataInterface as per the requirement.

For an overview and to know how this module can be used with OpenXCDataInterface module, please refer "An overview of new modules to add in MOTECH framework.docx" document.

To know on how this module has been developed and how one can use its APIs, please refer "Reference Document - mHealthDataInterface.docx" document.

====================
