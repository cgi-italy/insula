.. _known_issues:

Known Issues
============

While we strive to provide a seamless experience, there might be occasional hiccups. We're constantly working on improvements, and we appreciate your patience.

Below is a list of identified known issues. However, if you encounter any other unexpected behaviour please don't hesitate to report it to our support team at insula-ops.it@cgi.com.

Interactive Applications - Sharing does not work
------------------------------------------------

Currently, Interactive Applications (see :ref:`intellect_service_type`) cannot be shared. When a user shares an Interactive Application's job with another user, this user will be able to see the job in the Insula Intellect monitoring page, but will not be able to access the interactive application itself, i.e. when clicking on the link provided by the job a 404 error will appear.

Interactive Applications - SNAP Input File Issue
-------------------------------------------------

SNAP requires files to be opened manually, rather than automatically detecting the input files. The issue arises from the inability of SNAP to open the input file directly based on the default settings or path detection logic.

**Workaround**:
   - Open the input files manually in SNAP by navigating through the file menu:
   - Navigate to `File -> Open Product`
   - Locate the file at `/home/worker/workDir/inDir/input`
   
Interactive Applications - QGIS BSQ Dataset Compatibility Issue
---------------------------------------------------------------

There is a compatibility issue with BSQ datasets when used in QGIS. The dataset requires two files (.bsq and .hdr) to reside in the same directory in order to work. 
However, the downloader used for acquiring these files creates separate folders for each file, resulting in QGIS being unable to read them due to their separation.

There is no workaround at the moment.
