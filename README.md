
## Goal of Assignment

For the assignment build a prototype for the below: 
	Get detailed information about the types of cargo that a vehicle operator carries, as well as breakouts of the different vehicle types that operator uses

## Prerequisites

	Download Anaconda (for Python/R data science and machine learning on a single machine) from https://www.anaconda.com/
	Install anaconda.
	Once successful, you should be able to open 'Jupyter Notebook' - to start writing python code from browswer based editor.

## Installation/SetUp:

1. Download the input csv file from https://ai.fmcsa.dot.gov/SMS/Tools/Downloads.aspx
   Extract the input zip file (say) 'FMCSA_CENSUS1_2022Sep.zip' to get a folder 'FMCSA_CENSUS1_2022Sep'.
   Copy the FMCSA_CENSUS1_2022Sep/FMCSA_CENSUS1_2022Sep.csv into folder '.\census\FMCSA_CENSUS1_2022Sep'.
   
2. Change directory to the root directory to run python (.ipynb) from Jupyter notebook. 
	Example root directory: cd C:\Users\[user_name]
    Example: From cli, check you are able to access the downloaded input csv file, using either of below 2 commands: 
	 cd .\census\FMCSA_CENSUS1_2022Sep
	 cd C:\Users\[user_name]\census\FMCSA_CENSUS1_2022Sep
	 
3. Open Jupyter notebook (Python 3)

4. From Jupyter notebook(.ipynb), pip install below library/module:
	BeautifulSoup(python library for pulling data out of HTML), 
	requests(for API),
	pandas(to read csv as a dataframe)
	
5. From github, clone/download the code (ipynb) associated to the assignment: 'assignment_scraper_for_carrier_registration_details_Final.ipynb'

6. Copy the above assignment (.ipynb) to the root directory recognized by jupyer notebook. 
   cp assignment_scraper_for_carrier_registration_details_Final.ipynb C:\Users\[user_name]\census\FMCSA_CENSUS1_2022Sep


## Testing the installation

1. Run Jupyter Notebook.
2. Then, open 'assignment_scraper_for_carrier_registration_details_Final.ipynb'
3. Click 'Cell' menu -> 'Run All'

OUTPUT:
	Expected Output: You should see multiple csv files. Each file having the details associated to one operator.
	Output File Name format: DOT_NUMBER.csv
	CSV files created successfully for below operators(example) :- 
		1.csv
		10000.csv
		1000000.csv
		1000002.csv
		1000004.csv



