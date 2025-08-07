Demographic Data Analyzer

This project analyzes demographic data from a 1994 Census database using the Python library Pandas. The goal is to answer a series of questions about the dataset, including information about income, education, and various demographic groups.
Project Files

    demographic_data_analyzer.py: Contains the calculate_demographic_data() function, which performs all the required analysis and returns a dictionary of the results.

    main.py: A simple script to run the main function and print the output.

    adult.data.csv: The dataset used for the analysis.

How to Run

    Dependencies: Ensure you have Python and the Pandas library installed. If not, you can install Pandas using pip:

    pip install pandas

    Dataset: Make sure the adult.data.csv file is in the same directory as the Python scripts.

    Execution: Run main.py from your terminal to see the analysis results printed to the console:

    python main.py

Analysis Performed

The calculate_demographic_data() function computes the following statistics:

    The number of people of each race.

    The average age of men.

    The percentage of people with a Bachelor's degree.

    The percentage of people with advanced education (Bachelor's, Master's, Doctorate) who earn more than $50K.

    The percentage of people without advanced education who earn more than $50K.

    The minimum number of hours worked per week.

    The percentage of people working the minimum hours who earn more than $50K.

    The country with the highest percentage of high earners ($50K+) and the exact percentage.

    The most popular occupation for high earners in India.
