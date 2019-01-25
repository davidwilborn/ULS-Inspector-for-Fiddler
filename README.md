# ULS-Inspector-for-Fiddler
ULS Inspector for Fiddler

Installation
------------
Copy the UlsViewFiddlerExtension.dll file to your Fiddler inspectors folder, e.g. C:\Program Files (x86)\Fiddler2\Inspectors

How to use the inspector
------------------------
* A ULS tab will be displayed on your Inspectors tab for responses
* Click the "Select ULS Folder..." button on the tab
* Select the folder where the corresponding ULS logs are stored, which can either be a folder containing historical ULS logs, or the live ULS filder on a SharePoint server. This step only needs to be done once for a set of ULS logs.
* The inspector will then display ULS log entries that match the correlation ID from the current HTTP response. Clicking on a ULS entry will display the Message field above the log entries.
* Entries can be sorted by clicking column headers
* Click the "ULS Viewer" button to open the ULS file in ULSViewer.exe on the local machine (this must be installed seperately). The ULS file will be opened filtered to the current correlation ID. This filtering can be turned off by normal means.
