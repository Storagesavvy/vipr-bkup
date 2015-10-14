# vipr-bkup
Offhost Tool to backup EMC ViPR/CoprHD internal database data

Preliminary Plan:
  Create a tool that requests a new backupset to be created in the ViPR Controller Instance, after which the backupset will be downloaded and stored in a location specified by the user of the tool.
  
  This will leverage the ViPR REST API as documented for ViPR version 2.3
  
Note: the built in backup functionality for ViPR allows you to schedule a once per day backup, and send the backup to an external SFTP server.   The vipr-bkup tool is intended for users who do not have or want to use SFTP, and/or have different scheduling needs than 1 backup per day.

