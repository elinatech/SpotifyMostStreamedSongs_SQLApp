# Most Streamed Spotify Songs 2023 - Data Extraction with Python and MySQL

## GENERAL INFORMATION

This project extracts and analyzes data from the Most Streamed Spotify Songs 2023 dataset.
Title of Dataset: `Spotify Most Streamed Songs.csv`
Available on Kaggle (https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023). 

The script uses MySQL queries to interact with the dataset, enabling data manipulation and analysis.
Features:

    Extracts data from a CSV file and inserts it into a MySQL database.
    Allows users to perform SQL queries on the dataset.
    Provides a flexible configuration for database credentials and file paths.

## REQUIREMENTS

1. Python (Tested of verisons ≥3.12.4)  
2. Python Libraries: 
  `rich`,            For formatted terminal output, progress bars, and tables.
  `time`,            For delays in the "loading screen".
  `mysql.connector`, To establish connection between SQL and Python.
  `pandas`,          For data formatting and presenting, as well as reading the CSV file.
  `Ipython.display`, To display the SQL query outputs.
  `getpass`          To "hide" user input when prompted for a password
3. MySQL Database Server  
4. Dataset File (See Above)  
5. Python Script (`Group_8_Databases_BigData.py`)

Install the libraries using the following command on your Terminal:

```bash
pip install mysql-connector-python pandas getpass ipython rich
```

## SETUP INSTRUCTIONS

1. DOWNLOAD DATASET
    Obtain the dataset from Kaggle and place it in your desired location.

2.  RUN SCRIPT
    It is recommended to run the script in the `Terminal` or through an IDE like `VS Code` for best results.

3.  DATABASE CREDENTIALS AND FILEPATH
        You can either:
            a. Manually set the username, password, host, and filepath variables in the script.
            b. Let the script prompt you for these details after execution.

## HOW TO RUN

1.  Open your Terminal or your IDE.

2.   Navigate to the directory containing the script.
    <cd [your filepath]/Group_8_Databases_BigData.py>

3.  Execute the script:
    <python Group_8_Databases_BigData.py>

4.  Follow the on-screen instructions to input your MySQL credentials and dataset file path.


## NOTES
- Ensure that your MySQL server is running and accessible.
- Provide accurate credentials to establish a successful connection.

## SAMPLE OUTPUTS

The script allows you to run Queries such as:

- Top Charting Tracks Across Platforms
- Dynamic Music Playlist Generator
- Comparison of Track Analytics by Season of Release
- etc.

### TROUBLESHOOTING

If you encounter issues connecting to MySQL, verify that the username, password, and host are correct.
Check that the MySQL server is running and accessible on the specified host.

To ensure correctly viewed outputs, make sure your Terminal is extended.

## Academic Note
This project was completed as part of the final deliverable for the course Databases and Big Data at LUISS Guido Carli University (Rome). It was awarded full marks plus distinction for technical depth, innovation, and clarity.

## AUTHORS
#### (in alphabetical order of last names)

Last Name: Ateş, 
Name: Yasemin, 
ID: 304011, 
Email: yasemin.ates@studenti.luiss.it


Last Name: Basso, 
Name: Guia Ludovica, 
ID: 296881, 
Email: guialudovica.basso@studenti.luiss.it

Last Name: Giannotti, 
Name: Alessio, 
ID: 297961, 
Email: a.giannotti@studenti.luiss.it

Last Name: Yılmaz, 
Name: Elina, 
ID: 305561, 
Email: e.yilmaz@studenti.luiss.it
