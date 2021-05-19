# Foojay JDK Discovery API extension

A Visual Studio Code extension that gives the user the ability to select and download a JDK from different distributions.


When you've started the extension you have to open the 'command palette' by clicking on the gear icon in the lower
left corner of the Visual Studio Code application.

In the 'command palette' you simply type in or select 'foojay Discovery API' as shown on the following screen:
![command palette](https://github.com/HanSolo/discoextension/raw/main/DiscoExtension1.png)


### Quick
Now you should see the following screen where you can select a JDK to download (Quick). You can choose between the following JDK's
- JDK 8
- The latest LTS release (JDK 11 in November 2020)
- The current release (JDK 16 in May 2021)

![Quick](https://github.com/HanSolo/discoextension/raw/main/QuickSelect.png)

Simply select the major version you would like to download by selecting a radio button.
![Quick 2](https://github.com/HanSolo/discoextension/raw/main/QuickSelect2.png)

If you would like to change the archive type you can select it in the drop down box besides the version number.
It is also possible to change the distribution by clicking on the distribution link.

To download the selected JDK, please click on the blue area and choose a folder where the JDK should be installed.


### Drill down by version
That was the quick way of selecting a JDK but there are more possibilities.
If you select the "Drill down by Version" tab you will see the following screen:
![Drill down by version](https://github.com/HanSolo/discoextension/raw/main/DrillDownByVersion.png)

In this tab you can first select a major version and the extension will automatically select the latest available JDK from the default
distribution (Azul Zulu). If you now would like to change the JDK to another version or distribution you can check the "Details" checkbox.
You now can first select a specific version, then a specific Distribution and finally an archive type for download.

The download itself will again be triggered by pressing the blue box.


### Drill down by distribution
You could also drill down by distribution where you first select the distribution, followed by the major version, specific version and
archive type. Again the download itself will be triggered by pressing the blue box.
![Drill down by distribution](https://github.com/HanSolo/discoextension/raw/main/DrillDownByDistribution.png)


### Detailed
In the detailed tab you can select a JDK from a list that will be defined by your selection in the available drop down boxes for major version,
distribution, package type, operating system and archive type.
To download you have to select a JDK/JRE from the list by selecting it and after that press the "Download" button.
![Drill down by distribution](https://github.com/HanSolo/discoextension/raw/main/Detailed.png)


Attention:
Because the extension is written in JavaScript and HTML there is no way to visualize the progress of the downloading at the moment
due to cross domain restrictions.