Oracle User Creation & DMP Uplode
=================================
User Creation
=================================
Command:
=================================

Create User (Username) identified by (password)

grant dba to (Username)

=================================
Uplode DMP 
===================================================
Goto Run and Write down cmd

cmd-> command promt

command promt->imp

imp-> Enter

username: (Given user name while you created user in oracle)
password: (Given password while you created user in oracle)

import data only <yes/no> no> no

import File EXPDAT.DMP: Drug & Drop the dmp File.

Enter insert buffer size <minimum is 8192> 30720> 99999999

Export File created by Export: 009.00.01 via conventional path

Warning: the objects ware exported by system not by you

import done in WE8MSVIN1252 character set and AL16UTF16 NCHAR character set

List contents of import file only <yes/no> no> no

Ignore create error due to object existence <yes/no> no> Yes

Import grants <yes/no>: Yes> Yes

Import table data <yes/no>: Yes> Yes

Import entire export file <yes/no> no> Yes
---------------------------------------------
Import will be started 
---------------------------------------------
Finally Import Will be Completed Successfully  
