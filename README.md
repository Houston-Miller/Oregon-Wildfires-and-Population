# Oregon-Wildfires-and-Population

## About

Using data from reported wildfires and their causes, alongside census aggrigated population data, I will be combining these data sets to explore any correllation between population density, causes, occurances, and sizes of wildfires among the counties of Oregon.

## Data Sources

CSVs:<br><br>
<b>fire-occurence.csv</b><br>
The Fire Occurrence and Cause Data is a tabular dataset compiled by the Oregon Department of Forestry from the year 2000 to 2022. It contains statistical information about wildfires in Oregon during this period, including the serial number, fire category, year of occurrence, fire location (latitude and longitude), and cause of the fire (human or lightning and the general and specific causes). The data also includes information about the fire area, district and unit name, 
fire name, size, protected acres, and date and time of ignition, report, discovery, control, creation, and modification. Other fields include information about the land ownership type, township, range, section, subdivision, landmark location, county, land use restrictions, and fire district and unit codes.

<b>Oregon_Population_Estimates_By_v002.csv</b><br>
This Dataset is a collection of population data derived from the US Census Bureau to create an estimated population per county per year from 20010-2020 in the state of Oregon 

## Virtual Environment

Before you start to explore the project, please ensure you have met the following requirements:

- You have installed Python. This project was developed using Python 3.11.1. If you don't have Python installed or if you need to upgrade your current version, you can download it from the [official Python website](https://www.python.org/downloads/).
- You have installed Git, which is necessary to clone the repository. If you don't have Git installed, you can download it from the [official Git website](https://git-scm.com/downloads).

Follow these steps to run the project on your local machine:

1. **Clone the repository**

   Navigate to the directory where you want the cloned repository to be placed by using the ``cd`` command in your terminal, followed by the path of the directory.

   Then, you can clone this repository by running the following command in your terminal:

   git clone https://github.com/Houston-Miller/Oregon-Wildfires-and-Population
2. **Navigate to the cloned directory**

   Change your current directory to the cloned repository's directory data_analysis_capstone.
3. **Set up a virtual environment**

   Creating a virtual environment is recommended to keep the project's dependencies isolated from your system's Python environment. You can create a virtual environment using the following command:

   On Windows:

   ```
   python -m venv venv
   ```

   On macOS and Linux:

   ```
   python3 -m venv venv
   ```

   This will create a new virtual environment named `venv` in your current directory.
4. **Activate the virtual environment**

   Activate the virtual environment using the following command:

   On Windows:

   ```
   .\venv\Scripts\activate
   ```

   On macOS and Linux:

   ```
   source venv/bin/activate
   ```

   Your prompt should change to indicate that you are now operating within a Python virtual environment.
5. **Install the required packages**

   Install the required packages by running the following command:

   ```
   pip install -r requirements.txt
   ```

   You're now ready to run the project!
6. **Run the ``Main.ipynb`` file:**

   - If you have Jupyter Notebook installed, enter ``jupyter notebook`` and open the `.ipynb` file.
   - If you are using Visual Studio Code, open the `.ipynb` file and run the cells using the run button that appears at the top left of each cell, or simple press the Run All button at the top.

To deactivate the virtual environment when you're done, simply type `deactivate` in your terminal.

## Data Visualization

After cleaning and formatting the data I utilized a Tableau Dashboard to create visualizations of the complete data. [The Dashboard can be found here](https://public.tableau.com/app/profile/houston.miller/viz/OregonWildfire/OregonFireData)

## Conclusions and Further Questions

While the acreage burned from smoking fires is extremely low, moving into counties with much higher populations shows a significant increase in fires caused by smoking. Conversely, in more rural counties lightning fires burn much larger amounts of acres and show high reports of fires caused by lighting as well.

While showing high volues of reported fires as well, the areas outside of the higher centers of population density show high number of burns AND acres burned caused by equipment use. Potentially showing development in these areas or simply resource harvesting for the neighboring counties. 

## Data Analysis Capstone Requirements | Spring 2023

**Category 1: Loading Data:**

- Read TWO data files (JSON, CSV, Excel, etc.).

**Category 2: Clean and Operate the Data While Combining Them:**

- Clean your data and perform a pandas merge with your data sets, then calculate some new values based on the new data set.

**Category 3: Visualize/Present Your Data:**

- Make a Tableau dashboard to display your data.

**Category 4: Best Practices:**

- Utilize a virtual environment and include instructions in your README on how the user should set one up.

**Category 5: Interpretation of Your Data:**

- Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md. Tidy up your notebook, and make sure you don't have any empty cells or incomplete cells that don’t do anything. Make sure it’s all functional before your final github commit.
