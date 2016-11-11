# evacusync

## Summary

Data sync between the Evacuteer CiviCrm database and the central data store for the Evacuteer suite of systems.

## Details

Evacuteer uses a CiviCrm system to organize volunteers. This system current serves at the primary/master data store and is the system of record for information about volunteers.

The volunteer data is needed in the suite of Evacuteer systems, but the format that the data is stored at in CiviCrm is not ideal or access by applications or frameworks other than Drupal with CiviCrm.

This system pulls data from the CiviCrm instance and inserts it into a central database that can be more easily queried.

