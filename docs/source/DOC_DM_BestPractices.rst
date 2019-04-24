Organising your data
=====================
Difference between data and metadata? Why so important and what does it need to
comply to?

Types of datasets
~~~~~~~~~~~~~~~~~~

Environmental tabular data
+++++++++++++++++++++++++++
BCO-DMO can deal with a wide variety of data, including but not limited to biological,
chemical and physical oceanography measurements and experimental and model results.
We routinely deal with CTD, biological abundance, meteorological, nutrient, pH, carbonate,
PAR, sea surface temperature, heat and momentum flux, sediment composition, trace metals,
primary production, pigment concentration measurements, images and movies.

Sequencing data
++++++++++++++++
While sequence data should be sent to GenBank, sequence accession numbers and the associated
environmental data can be contributed to BCO-DMO and we can provide the links to the sequence
repository. This ensures that the data are discoverable from BCO-DMO's website. Please see
"Contributing Sequence Accession Numbers" for more information.

Modelling and raster/grid data
+++++++++++++++++++++++++++++++
We're still developing our strategy for the management of modeling data, but for now,
we ask submitters to provide the input and output files and code. In this case, we'll serve
both the raw output as well as the processed matrices. Please also include documentation with a
level of detail that makes the code usable and intelligible, including a description of the source
files, version numbers, and any code configurations, settings, etc. used to generate the results.


Formats of data
~~~~~~~~~~~~~~~
The most used format data is been submitted to BCO-DMO is tabular data.


Tabular data
++++++++++++++++
Tabular data in ASCII, .xls(x)

A dataset is a logical collection of data files, often organized as one or more tables.
In the context of BCO-DMO, a dataset might be a series of CTD casts from one or more cruises,
a table from a publication, a sheet from an Excel file containing the conditions adxfcnd results of
a controlled experiment, etc. If the column headings for several tables/spreadsheets are the same,
they can often be combined into a single dataset. A study will often yield multiple tables (datasets)
associated with it, each requiring its own submission form. You should fill out one dataset
submission form for each dataset. If you have further questions, don't hesitate to ask.

It is important that the data be managed in such a way that they are discoverable and reusable
by others. This means that there is sufficient metadata to support proper data reuse and that
the actual data, not just resulting graphs, are accessible.


* Remove formatting that will not be preserved when exported as a plain text file (e.g. color, merged cells, plots, etc.)
* Only include oen tabular dataset (i.e. table) per Excel sheet
* Ensure cells contain intended values. Check formula results, references to other sheers, hyperlinks etc.

Good reference articles for data organisation:

* Data organisation in Excel: https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1375989
* Data organisation in spreadsheets for Ecologists: https://datacarpentry.org/spreadsheet-ecology-lesson/


Grid/Raster data
+++++++++++++++++


Controlled vocabulary
~~~~~~~~~~~~~~~~~~~~~

Parameters - Titles
++++++++++++++++++++
Unites, description

Instruments
+++++++++++

Locations
~~~~~~~~~
latitude and longitude of sampling locations

Date-time parameters
~~~~~~~~~~~~~~~~~~~~~
* Document your time and fata format including time zon (e.g. UTC, UTC+02, local EST)
* Check for inconsistent date/time formatting
* In-situ data: include date/time and lat/longer* Experimental data: include data/time of experiments
  if applicable
* ISO datetime?

Large data
~~~~~~~~~~
For large volumes of data we suggest using Dropbox. Please see https://www.dropbox.com/.
If you don't have your own Dropbox account, a BCO-DMO Data Manager will set up a folder
for you and send you a URL that will allow you to upload your data into our Dropbox using
your browser.

Another option is to make the files available online (ftp, Google Drive, etc.)
and let us know how to get them.  If you still have questions, please contact us for
alternative approaches.

Quality Assessment
~~~~~~~~~~~~~~~~~~~
Level of curation

Metadata
~~~~~~~~~
For your data to be reused by other researcher, it needs context, such as where and how it was
collectedm analysis methods, funding resources, etc. This information is known as metadata. The metadata
you provide about your data through the form should be thorough, complete and publication ready. The contents of your
metadata form are directly used to popuate your public Dataset Landing Page.
