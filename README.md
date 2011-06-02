This Python script uploads a file to Confluence as an attachment. The space key and page title are specified on the command line.

Parameters
============
The parameters are, in order:

* Space key of the page where you want to attach the file. For example, "KEY".
* Page title of the page where you want to attach the file. The page must already exist. You may need to escape or quote special characters in the file name. For example, "Page title".
* File name of the file to attach. This will also be used as the name of the attachment within Confluence. For example, "somefile.txt".

Version History
===============
Matt Ryall (Atlassian):

* 1.0 - first release
* 1.1 - fix upload for binary files

Geoffrey Huntley (@ghuntley):

* v1.2 - added autodetection of attachment mimetype and configuration file.
