### Required Packages:

Python: pandas, numpy, scikit-learn, itertools, matplotlib.pyplot, IPython.display, seaborn, altair, datashader.

### Introduction: Vehicle Abandonment in Philadelphia
According to Philadelphia Police department, a motor vehicle is classified as abandoned:
1. One that is physically inoperable and is left unattended on a highway or other
public property for more than forty-eight (48) hours.
2. Has remained illegally parked on a highway or other public property for a period
of more than forty-eight (48) hours.
3. That is left unattended on or along a highway or other public property for more
than forty-eight (48) hours and does not bear all of the following:
a. Valid registration plate.
b. A current certificate of inspection.
c. An ascertainable vehicle identification number.
4. Has remained on private property without the consent of the owner or person in
control of the property for more than twenty-four (24) hours.
5. Is found to have a vehicle registration and inspection sticker, both of which are
expired for a period exceeding ninety (90) days.

### Data Source: 

The primary data source for this project is from OpenDataPhilly. The 311 Service and Information requests data represents all service and information requests since December 8th, 2014 submitted to Philly311 via the 311 mobile application, calls, walk-ins, emails, the 311 website or social media. [311 Service and information Requests](https://www.opendataphilly.org/dataset/311-service-and-information requests)

Moreover, I used the crime data set from Open Philly to get the reported prostitution incidents.Crime incidents from the Philadelphia Police Department. Part I crimes include violent offenses such as aggravated assault, rape, arson, among others. Part II crimes include simple assault, prostitution, gambling, fraud, and other non-violent offenses. [Crime_Incidents](https://www.opendataphilly.org/dataset/crime-incidents).This dataset previously had separate endpoints for various years and types of incidents. These have since been consolidated into a single dataset.

Finally, I will used neighborhood data by Zillow to spatially join the requests to the neighborhoods to visualize the number of vehicle abandonment in the neighborhoods of Philadelphia and the number of prostitution incidents in Philadelphia.
