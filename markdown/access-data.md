# Access-Data

## Discovering

Once data are processed and published online, the BCO-DMO website enables data **discovery** via **text and geospatial search interefaces**, making it easy for users to find datasets of choice.

### Text-based search

Through text-based searches, the database can be searched by cruise, project, person, or any keyword provided in metadata upon submission. Access to data is made possible from the Dataset Landing Pages, and data may be subsetted, plotted and reformatted prior to download.

Text-based access to the data and information managed by BCO-DMO is provided by the Drupal content management system \(CMS\). Drupal, a CMS freely available to anyone, manages the more or less static web pages, including information about BCO-DMO and how to contact and contribute data to BCO-DMO, and manages the metadata, that is, the information about the data.

Data are accessed by clicking on one of the broad categories listed to the left on the web page including Programs, Projects, Deployments, Datasets, Instruments, Parameters, People, Affiliations, Funding, and Award numbers. Once on one of these pages, one can do a word search such as looking for a particular person, or a particular kind of data. For example, clicking on 'Datasets' and then searching for 'coral' results in a list of many datasets. If you are looking for the results from a particular project, try searching the Projects or People.

Once a dataset of interest has been located, there will be a 'Get Data' button near the top of the page. Clicking on this will bring up the data in table form. From the data display: Click on blue links to drill down into the data or click on the 'Next Level' button to see all the data at the next level. Click the 'Flat Listing' after there are no more hyperlinks to get all the data. At this point, you can copy and paste the data into an Excel or text file. You can see an alternate view of publicly accessible metadata by clicking on the Documentation link at the top of the data display page.

The BCO-DMO database encompasses the full range of oceanographic measurement types from limnological, physical, chemical, biological and/or ecological and biogeochemical sub-domains

### Geospatial search

There are several ways that websites provide geospatial access to geospatially enabled data. We sought a solution that would be data driven \(that is, display data directly from our metadata database and data servers and not have to rely on pre-made maps and images\), and use open source software. We decided on the MapServer software, initially developed by the University of Minnesota.

The MapServer software has several advantages, including its dependence on standards, such as OGC's Web Mapping Service. We were also lucky enough to have our contract programmer, Charlton Galvarino, be very proficient in using this package, so he has been able to tailor the interface extensively to suit our users' needs.

MapServer, because of its OGC underpinnings, enabled us to provide Web Feature Service \(WFS\) access to our data with little effort.

Our metadata database provides the basis for all of the maps generated on the fly and displayed on the user's browser. However, we also wanted people to be able to view the data on the browser as well. We are interested in enabling the user to decide whether the datasets are of sufficient interest to warrant their download to their own platform for further analysis and study. However, we do not intend to provide the analysis software via our web site. We do not want to decide how to contour the raw data into a regular grid, for example. These decisions are up to the investigator to pursue once they have the data with which to work.

To facilitate the viewing of data, we provide several ways of displaying data. These include:

> Basic X-Y plot \(such as salinity versus depth\) Abundance plots \(circle size log proportional to count or weight\) So called time-series plots X-Y plots of data from multiple stations
>
> Ability to display the data when the data are themselves images or movies

Since we wanted to facilitate the downloading of the data \(not just the metadata\) we added the Web Feature Service OGC protocol to our list of download options, which already included downloads as ASCII \(tab, comma and space separated\), Matlab binary file, netCDF, ODV and KML files. KML files can be used by such applications as Google Earth and Google Maps.

## Citing data and the use of a DOI

Correctly citing and therefore giving credit to the researcher that made the data publicly available is one of terms of use. We provide a "get citation" button on each dataset page for easy use of reserachers. In general citations should include the following:

> Citations should include the following:
>
> > Principal Investigator \(PI\) name\(s\) title of dataset data version date publisher or distributor, date accessed/retrieved by you DOI or URL of the data set

Example Data Set Citations:

Buesseler, K. \(2006\) “VERTIGO Cruise Event Log.” Biological and Chemical Oceanography Data Management Office \(BCO-DMO\). Dataset version: 5 September 2006. [http://www.bco-dmo.org/dataset/2957](http://www.bco-dmo.org/dataset/2957) \[access date\]

Twining, B. \(2016\). “Element Quotas of Individual Synechococcus Cells Collected During Bermuda Atlantic Time-Series Study \(BATS\) Cruises Aboard the R/V Atlantic Explorer between 2012-07-11 and 2013-10-13”. Biological and Chemical Oceanography Data Management Office \(BCO-DMO\) Dataset version 05/06/2016. &lt;doi:10.1575/1912/bco-dmo.651474&gt; \[access date\]

## Available formats

Data can be downloaded from BCO-DMO as tab-, comma-, and space-separated ASCII files, Matlab binary files, netCDF format \(if the data are amenable to this format\), and ODV format \(if the data are amenable to this format\).

Data can also be accessed using Open Geospatial Consortium’s \(OGC\) Web Mapping Service \(WMS\) and Web Feature Service \(WFS\) through our MapServer interface. For more information on finding and downloading data using the BCO-DMO data system, please refer to our Data Access Tutorial \(PDF\).

