Structuring datasets and metadata
=================================
Difference between data and metadata? Why so important and what does it need to
comply to?

If you are interested in data management, DataOne has on-line education modules
that can help with data organising https://www.dataone.org/education-modules


Tabular data
~~~~~~~~~~~~~
Content tabular data?
-----------------------------
The majority of data that BCO-DMO is curating consists of tabular data. The
range of the **different data types is huge**. It includes, but is not limited by
biological, chemical and physical oceanography measurements and experimental
and model results. We routinely deal with CTD, biological abundance,
meteorological, nutrient, pH, carbonate, PAR, sea surface temperature, heat and
momentum flux, sediment composition, trace metals, primary production, pigment
concentration measurements, images and movies.

Formatting tabular data
------------------------
Tabular data files can consist in different formats: ASCI, .xls(x), .ODS etc.
These tabular files should be organised and submitted to BCO-DMO per dataset.

A **dataset** is a logical collection of data files, often organized as one or
more tables. In the context of BCO-DMO, a dataset might be a series of CTD casts
from one or more cruises, a table from a publication, a sheet from an Excel file
containing the conditions adxfcnd results of a controlled experiment, etc.
**include only one tabular dataset (i.e. table) per Excel sheet.**

If the **column headings** for several tables/spreadsheets are the same, they
can often be **combined into a single dataset**. A study will often yield multiple
tables (datasets) associated with it, each requiring its own submission form.
You should fill out one dataset submission form for each dataset. If you have
further questions, don't hesitate to ask.

Datasets will be exported to a **plain text file**, which means it cannnot
preserve rich text formatting (such as excel). Therefore **formatting such as**
**color, merged cells, plots, etc. need to be deleted**

Ensure cells contain intended values. Check formula results, references to other
sheers, hyperlinks etc.

Good reference articles for data organisation:

* `Data organisation in Excel`_
* `Data organisation in spreadsheets for Ecologists`_

.. _`Data organisation in Excel`: https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1375989
.. _`Data organisation in spreadsheets for Ecologists`: https://datacarpentry.org/spreadsheet-ecology-lesson/


Special cases: Sequence data
-----------------------------
While sequence data should be sent to GenBank, sequence accession numbers and
the associated environmental data can be contributed to BCO-DMO and we can
provide the links to the sequence repository. This ensures that the data are
discoverable from BCO-DMO's website. Please see "Contributing Sequence Accession
Numbers" for more information.



Modelling and raster/grid data
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
We're still developing our strategy for the management of modeling data, but
for now, we ask submitters to provide the input and output files and code. In
this case, we'll serve both the raw output as well as the processed matrices.
Please also include documentation with a level of detail that makes the code
usable and intelligible, including a description of the source files, version
numbers, and any code configurations, settings, etc. used to generate the
results.

Metadata
~~~~~~~~~
Metadata is documentation about the data. It describes the content, quality,
condition, analysis methods and other characteristics of a dataset. In othere
words, metadata adds **context** to your data. It **allows data to be discovered,**
**understood, reused and by other researchers.**

BCO-DMO provides a standardized metadata form that need to be filled in when
datasets are being submitted. See section "Contribute Data" to find these forms.
The metadata you provide about your data through the form should be thorough,
complete and publication ready.

The contents of your **metadata form** are **directly used to popuate your public**
**Dataset Landing Page.**


Standardised vocabulary
~~~~~~~~~~~~~~~~~~~~~~~~
The importance of standardised vocabulary

Parameters - Titles
---------------------
Unites, description

Instruments
-----------

Locations
---------
latitude and longitude of sampling locations

Date-time parameters
--------------------
* Document your time and fata format including time zon (e.g. UTC, UTC+02,
  local EST)
* Check for inconsistent date/time formatting
* In-situ data: include date/time and lat/longer* Experimental data: include
  data/time of experiments
  if applicable
* ISO datetime?



Quality Assessment
~~~~~~~~~~~~~~~~~~~
Level of curation
When your data is submitted, a data manager will be assigned that will assess
if your data complies to the "rules" of Good data management.

Our philosophy about data management is to intrude as little as possible
