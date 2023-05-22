# King Saud University Course Content Scraper

This code is a Jupyter Notebook (.ipynb) designed for scraping the course content of King Saud University. It allows you to retrieve the course information for a specific college, major, and major plan.

## Usage

Follow the steps below to use the code:

1. **Change the College Name:** Open the Jupyter Notebook file and modify the "college_name" variable to the desired college name.

2. **Change the Major:** Update the "major_name" variable with the desired major.

3. **Pick the Right Major Plan:** Modify the "major_plan" variable to select the appropriate major plan for scraping.

4. **Set the While Loop Counter:** Adjust the "num_pages" variable to match the number of pages of the major you want to scrape. This ensures that the scraping process covers all the relevant pages.

5. **Scrape and Save to CSV:** After making the necessary changes, execute the code to scrape the course content. Once the scraping is complete, the resulting data will be saved to a CSV file. You can choose any name for the CSV file.

6. **Cleaning the Data:** Navigate to the "cleaning.ipynb" file. Open it and read the CSV file you saved in the previous step.

7. **Running the Cleaning Process:** Execute all the cells in the "cleaning.ipynb" notebook. Please ensure that at the end of the cleaning process, you rename the file to match the name of the CSV file you read in the previous step.

## Dependencies

Make sure to install the following dependencies before running the code:

- Helium: Install using `pip install helium`.
- time
- numpy: Install using `pip install numpy`.
- pandas: Install using `pip install pandas`.
- re
- warnings
- threading

**Note:** You can install the required Python packages by running `pip install -r requirements.txt`.
**Note:** Error messages should disappear when you run the code. (I just couldn't figure out how to hide them sorry)

Feel free to reach out if you have any questions or encounter any issues while using this code.

Happy scraping!
