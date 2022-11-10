# Introduction to CSV and JSON

In the last exercise, we saw how we can read the data stored in log files and parse the files to generate reports.
Log files or Text files are an example of what we call Raw text data. Text that doesn't have a specific data structure specified in the format of the file.

However, most of the times you would work with data that has some structure. Some common examples include excel sheets, databases, JSON, XML etc. And, you have to process that data find some insights.


For this excercise, let's assume you work as a data analyst at a Healthcare startup and you have to analyse Covid-19 research data stored in JSON files and generate CSV.


JSON and CSV are two of the most popular formats for storing and processing data.


1. Build on Python skills you learned in the previous unit by expanding your knowledge of writing, reading, and parsing data in formats like JSON and CSV.
2. Learn how to use Python libraries like Pandas and json.


## CSV

**Tabular data** is a spreadsheet format like what you'd see in Excel or Google Sheets. It has rows and columns. Often, each row will be a single observation and each column will be a specific variable. The same variables will be recorded for each observation (or else you have empty columns in some rows).
File formats: .csv, .tsv, .xls, .xlsx

CSV Stands for "Comma Separated Values"


## JSON

**Hierarchical** data is data format where values can be nested within each other. With hierarchical data structures, you can have different information about each observation. You generally want to try to avoid trying to "flatten" hierarchical data into a tabular data structure because it's often not space efficient. For example, if you have a dataset of food products and clothes products, you probably want to know the expiration date for the food and the clothing size for the clothes. In a hierarchical structure you don't need to specify that you don't know the size for the food or the expiration date for the clothes, but in a tabular data structure you would. As a result, you'd end up with a lot of NA cells that aren't very informative and waste space.
File formats: .json, .xml