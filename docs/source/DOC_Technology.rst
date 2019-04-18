Behind the scenes
==========================
Technical infrastrcuture
~~~~~~~~~~~~~~~~~~~~~~~~~~
The existence of BCO-DMO falls or rises with the technical infrastructure.

Security
~~~~~~~~~~
This is secret

The JGOF GLobec data management system
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


The JGOFS/GLOBEC Data Management System permits data to be served from any computer capable of running the software (currently Unix-based machines). It is also possible, and in may ways preferable, if the contributor serves their data from their own computer. The serving software is available via ftp (ftp://globec.whoi.edu/pub/software/JGOFS_GLOBEC/). The only other requirement is that your computer have web-serving software installed, such as Apache. (If your computer has a web site, then it has this software already available.) While it is possible to install the JGOFS/GLOBEC software yourself and populate it with your data on your own, many have found it useful to contact the Data Management Office for help and suggestions. If you wish, the DMO will install the software on your machine and get things set up for you. No special privileges are required to install the software, although your Webmaster will need to define an entry (called a ScriptAlias) in the httpd.conf web server configuration file so your web server knows where to look for the software.
Data Serving Guidelines

There are several guidelines about how to organize and submit your data to BCO-DMO. However, the main strength of the system is that it can accommodate almost any kind of data with a suitably written method (i.e. computer program). But when several people collect similar data sets it will make it easier for people to retrieve the data for subsequent review and analysis if some guidelines are followed.

These guidelines are as follows:

    Data are structured hierarchically with the slowest changing variable first (e.g. cruiseid, leg, station, then cast number).
    Use variable/parameter names recommended by BCO-DMO. If your variable is not in the recommended list, please contact the Data Management Office (info@bco-dmo.org) so we can add it.

The submission and serving of data is an iterative process. The data contributor and the Data Management Office work together to serve the data in a way and at a time that is most useful to the contributor and the scientific community as a whole. The data can be easily re-submitted and re-served if later processing improves data quality
Adding Your Data

To add data to BCO-DMO, take the following steps:

    Decide where data will reside. If you wish to 'serve' the data from your own machine, you can download a copy of the JGOFS/GLOBEC data management software from the following web site: ftp://globec.whoi.edu/pub/software/JGOFS_GLOBEC/. We will assist you in its installation. At this point the server computer must be running a UNIX-based operating system. If you do not wish to 'serve' your data from your own machine, the data may reside instead on a BCO-DMO server.
    Organize the data in a way that is useful for your needs. Chances are that is how the data will be useful to others. If you have your own data management system and want to use it, such as Oracle or MySQL, by all means use it. We have methods that can extract these data out of your system and serve them via the U.S. JGOFS/U.S. GLOBEC data management system more or less automatically. If you prefer to use your data from a spreadsheet (e.g. an EXCEL spreadsheet), that is fine too. In that case, we will extract the data from the spreadsheet into ASCII and serve the data that way. We often reorganize the data into what is called a hierarchical form as described above, to foster unique retrieval of values. This reorganization can also be done automatically so you need not take the time to reorganize your data before contributing the data to BCO-DMO.
    Please consult the list of BCO-DMO parameters names currently available (http://osprey.bco-dmo.org/parameter.cfm). It is much easier to compare results if people use a common set of parameter names. Contact the DMO if there are field names that you require that are not yet defined. We will work with you to create new names that meet your needs.
    Create the information necessary in order to use these data. This includes a description of the field names used, the data collection and data processing methodology and steps taken to produce these data, and an explanation of unusual values, including missing data. Provide the Data Management Office with the names of people contributing the data and the names of people who should be contacted with questions, if different. Keep in mind the long-term use of these data and please do not specify a graduate student as the sole contact. The material can be provided in an e-mail to the Data Management Office by completing our Dataset Metadata Form. This information is usually referred to as metadata. Metadata is the information not already contained within the data file that makes the data truly useful to others.

Accessing Data

Of course, a data management system would have very little use unless one could extract data from it. The JGOFS/GLOBEC system allows you to select data meeting specified criteria (e.g. all data where depth is greater than 120 meters); project data (e.g. only show me the latitude, longitude, date and sea surface temperature values); join data with attributes in common; make a simple X-Y plot to check trends; do a few rudimentary statistical counts; and, perhaps most importantly, download the outcome of your selection and projection operations as a simple text (ASCII) table (CSV and TSV), as a Matlab-compatible binary file, as an ODV (Ocean Data View) file (when required data values are available), and as a NetCDF file.
