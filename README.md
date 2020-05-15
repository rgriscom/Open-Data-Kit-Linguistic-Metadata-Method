# Open Data Kit Linguistic Metadata Method
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
This repository hosts documentation and resources for the ODK linguistic metadata method. The resources include two sets of forms for use by linguists who want to use ODK to collect metadata in remote areas. 

## Method Description
### ODK Aggregate
The first step is to prepare your server. If you don't have your own physical server, you can set up a virtual server using [Google Cloud Platform](https://cloud.google.com) or [Amazon Web Services](https://aws.amazon.com/). There is [documentation of the steps to set up a server](https://docs.getodk.org/aggregate-setup/) on the ODK website.  

### ODK Build
Create an account with [ODK Build](https://build.getodk.org/) and upload one of the following sets of forms:
1. **Multiple Choice Forms**: These forms have multiple choice widgets for a number of questions that need to be filled out before you can use the form to collect data. For example, the question asking for the name of the researcher has five options (i.e. "Research #1", "Research #2", etc.), and you need to manually change the labels for these answers and add or remove answers as needed. These forms are best for larger projects involving multiple researchers or large amounts of data.
2. **Open Text Forms**: These forms can be used more or less out of the box, but they often require text entry for many fields. For example, the name of the researcher who is collecting data must be entered manually. These forms are best for smaller projects with fewer researchers or less data. 

Both types of form are based on the metadata profile for the Endangered Languages Archive (ELAR). If you would like a form for a different metadata profile, feel free to send an email to rgriscom@gmail.com

Once you have prepared your forms you can upload them to your Aggregate server directly from ODK Build. If you visit the server, then you can confirm that the forms have been successfully uploaded.

[Further documentation of ODK Build](https://docs.getodk.org/build-intro/) can be found on the ODK website.

### ODK Collect
The final step is to prepare ODK Collect on an Android device. The app can be found in the Google Play Store. After the app has been installed, you  must enter the information for your Aggregate server in the settings. You are then able to download forms from the Aggregate server, fill them out, and upload them back to the server.

[Further documentation of ODK Collect](https://docs.getodk.org/collect-intro/) can be found on the ODK website.




