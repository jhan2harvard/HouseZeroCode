This README.txt file was generated on 2023-06-01 by Jung Min Han of CGBC.

GENERAL INFORMATION

1. Title of Dataset: HouseZero Dataset: A Three-Year Dataset of Energy, Indoor Environment, and System Operational Performance for an Ultra-low Energy Office Building

2. Author Information
	A. Principal Investigator Contact Information
		Name: Ali Malkawi
		Institution: Harvard Center for Green Buildings and Cities
		Address: 20 Sumner Rd, Cambridge, MA 02138
		Email: amalkawi@gsd.harvard.edu

	B. First Author Contact Information
		Name: Jung Min Han
		Institution: Harvard Center for Green Buildings and Cities
		Address: 20 Sumner Rd, Cambridge, MA 02138
		Email: jhan2@gsd.harvard.edu

	C. Corresponding Author Contact Information
		Name: Xu Han
		Institution: Harvard Center for Green Buildings and Cities
		Address: 20 Sumner Rd, Cambridge, MA 02138
		Email: xuhan@gsd.harvard.edu

	D. Data Support Contact Information
		Name: Pete Howard 
		Institution: Harvard Center for Green Buildings and Cities
		Address: 20 Sumner Rd, Cambridge, MA 02138
		Email: phoward@gsd.harvard.edu


3. Date of data collection (single date, range, approximate date): 2020-06-01 to 2023-05-31

4. Geographic location of data collection: 20 Sumner Road, Cambridge, MA, USA

5. Information about funding sources that supported the collection of the data: The data collection and processing efforts were supported by the Harvard Center for Green Buildings and Cities(CGBC).


SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data: We will follow Harvard policy(Placeholder)

2. Links to publications that cite or use the data: N/A

3. Links to other publicly accessible locations of the data: https://datadryad.org/HouseZeroData(Placeholder)

4. Links/relationships to ancillary data sets: N/A

5. Was data derived from another source? No 

6. Recommended citation for this dataset:  J.M. Han, Malkawi. A, S. Lim, X. Han, P. Howard, E. Chen, A. Three-Year Dataset of Energy, Indoor Environment, and System Operational Performance for an Ultra-low Energy Office Building. submitted to Nature Scientific Data, under review.


DATA & FILE OVERVIEW

1. File List: 
	- HouseZero Data: This folder contains 30 time-series data files in CSV format, covering energy use data, indoor and outdoor environmental data, and HVAC operational data. 
			  The data has been processed using the data processing script (https://github.com/jhan2harvard/HouseZeroData(Placeholder)) to fill in the missing data.
	- HouseZero Data Report: This doc file contains all missing periods including long-term missing periods with ML imputation and short-term missing periods with no data imputation. 

2. Relationship between files, if important: Users can obtain the missing data information from the data report. 

3. Additional related data collected that was not included in the current data package: N/A

4. Are there multiple versions of the dataset? No


METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 
	The data collected and reported on comes from various sensors, systems, and meters located throughout the house. (Network paper Cite)
	Indoor environmental sensors – temperature, humidity, and CO2 are connected to building automation controllers, 
					these values are collected at 1-minute intervals and stored on the building automation server for long-term archiving and reporting.
	For the local weather data, the data is collected from a separate measurement and reporting system connected to the campus network.
	The same can be said for electrical circuit metering, PV metering, and GeoThermal metering systems.

2. Methods for processing the data: 
We identified and modified the missing data and outlier values to generate a clean version of the time-series data. Specifically, we used statistical methods and machine learning algorithms (e.g., linear interpolation, K-nearest neighbors, decision tree, random forest algorithms) to fill the missing periods by considering both the length of the data gap and the sampling frequency of each data point. More detailed description can be found at: https://github.com/jhan2harvard/HouseZeroData/Cleaning(Placeholder)

3. Instrument- or software-specific information needed to interpret the data: 
- The time-series data is stored in CSV format, which can be further interpreted in any software/tool (e.g., Microsoft Excel, Python Interpreters).

4. Standards and calibration information, if appropriate: N/A

5. Environmental/experimental conditions: The data were collected from an office building under real operating conditions.

6. Describe any quality-assurance procedures performed on the data: We cleaned the dataset by filtering the outliers and filling in the missing periods.

7. People involved with sample collection, processing, analysis, and/or submission: J.M. Han, Malkawi. A, S. Lim, X. Han, P. Howard, E. Chen, A. all from CGBC. 


DATA-SPECIFIC INFORMATION FOR: HouseZero Data Report.pdf

We have 33 time-series data files in CSV format. We summarized the following information for each file in a separate doc file, titled "HouseZero Data Report.pdf".

Name of Variables:

Number of Years:

Missing Periods List:

Missing Data Imputation Status:
