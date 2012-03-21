***********************************************************************
*                       TYPSoft FTP Server 1.10                       *
***********************************************************************

TYPSoft FTP Server is a fast and easy ftp server with support to
Standard FTP Command, Clean interface, Virtual File System
architecture, ability to resume Download and Upload, IP Restriction, 
Login/Quit message, logs, Multi Language and many other things.


Innovations
-----------

1.10
- In reality, this version is the version 1.09 but I didn't include the
  good exe in the installation :( This is what happen when you work
  with many different version of the same product...

1.09
- Now user need to have the Delete Right to overwrite a file on Upload.
- Have remove the list of IP in User Info. Too much confusion for
  unexperience user.
- Add an option to specify the IP for PASV mode.
- Fixing a bug with Virtual Directory and Directory when they have a 
  space.
- Other minor bug fix and optimization.

1.08
- Fix a long know bug in TFS with passing the -n parameters in *NIX FTP
  program in command line.

1.07
- Fix a bug introduces in the last version. All upload files go in the
  home directory.

1.06
- Fix a bug with the creation of directory with the virtual link system.

1.05
- Fix a bug introduces in the CWD command in the last version.

1.04
- Fixing a security bug. When a user has upload access without having
  Sub Directory include, the user can overwrite any file on the system.
  Thank to Egor Chusov for this one.
- Adding an option to specify the PASV range port used by TFS. Now, if
  you have a router/firewall, you can forward only some port and not
  all port from 1024 to 65535 on your IP.

1.03
- Arrgg.  An option of the compiler that I activate in the past for 
  debug a function, which gives me all error evens those which I said 
  to pass over: /

1.02
- Fix a bug introduces into the version 1.01. No body was able to go in 
  Virtual Link after the bug fix for the ".." in filename and directory.

1.01
- Fix a problem when selecting a user after shorting the list by ID.
  Didn't select the good one.
- Make path answer more Unix Style.
- Fix a bug with some directory who not hidden when Sub Directory 
  Include was unchecked.
- Fix a bug when Virtual Right been selected but no name was given.
  This is given an "Out of List Bound" error.
- Fix a bug with "LS" command. The Virtual link was not displayed.
- Fix a bug with Directory and filename with ".." in the name.

1.00    
- First final version. Remove beta status.


***********************************************************************

TYPSoft
Innovation is our sphere...

Home Page: http://www.typsoft.com
E-Mail: webmaster@typsoft.com

***********************************************************************