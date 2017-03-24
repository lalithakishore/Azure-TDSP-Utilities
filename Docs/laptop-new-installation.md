# Setting up a new windows laptop 

Following is a non-exhaustive list of software and tools that are useful as you work on data science projects on Azure from a windows pc.

## Getting started

- **OneNote**: log in your Account and make sure your notebook are stored in OneDrive to be able to access them from anywhere

- **Outlook**: log in your Account. On the mail view of outlook, right click on the calendar icon at the bottom left and `dock the peek` to have your daily appointments showing directly in outlook

- **Ubuntu for Windows**: In the windows security settings, turn on developer mode. You might see an error code, it's actually not a real error. Then search with cortana 'Turn windows features on or off' and turn on the Windows Subsystem for Linux. Then you can restart your computer and you should have `bash` available as one of your programs.

## Software

- [**Chrome**](https://www.google.co.uk/chrome/browser/desktop/): Microsoft Edge is a big improvement over IE, but it seems that Edge does not handle well pages with large memory requirements and crashes. 

- [**Visual Studio Code**](https://code.visualstudio.com/Download): A light weight text/code editor, comes with thousands of available extension. Tip: When editing Markdown `ctrl+k` `v` gives you instant preview.

- [**Visual Studio**](https://www.visualstudio.com/post-download-vs?sku=ent&clcid=0x409&downloadrename=true): Visual Studio is a full fledged IDE that comes in with numerous plugins and extensions to interact with the different services of the Azure platform.

- [**SQL Server Management Studio (SSMS)**](https://msdn.microsoft.com/en-us/library/mt238290.aspx): This software lets you manage and interact with your Azure SQL Databases and Azure Data Warehouse.

- [**Git bash**](https://git-scm.com/download/win): Install git on windows, this also comes with a bash command line which might seem redundant with Ubuntu on Windows, but it comes with a nifty right click 'open git bash here' which can be really useful.

- [**Source Tree**](https://www.sourcetreeapp.com/) Git UI client, probably the most usable git client out there.

- [**Microsoft Azure Storage Explorer**](http://storageexplorer.com/) Client to interact with Azure blobs and fileshares from your pc

- [**AzCopy**](https://azure.microsoft.com/en-gb/documentation/articles/storage-use-azcopy/) Microsoft Azure Storage Explorer is good enough for files < 1GB, but it can be slow when uploading or downloading several GBs. For bigger jobs you can use AzCopy command line tools

- [**MobaXterm**](http://mobaxterm.mobatek.net/download-home-edition.html) Enhanced terminal for Windows with X11 server, tabbed SSH client, network tools and much more



## Data Science


- [**R**](https://www.rstudio.com/products/rstudio/download2/): R studio client is available for windows. You can also run R studio server from a linux DSVM.

- [**Anaconda**](https://www.continuum.io/downloads): You can download the windows or the linux version. If you download the linux version, you can install it using ubuntu for windows.

- [**Power BI**](https://powerbi.microsoft.com/en-us/desktop/) The desktop version of Power BI has more features than the online or app version.
