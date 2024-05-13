# Automated Daily Sales Data Summary Program

## Overview
This project involves the development of an automated program to efficiently summarize daily sales data retrieved from a data warehouse (Google BigQuery). The program is designed to tailor the summarized data format according to the specific requirements of each mall and transmit it to individual outlet malls' management via SFTP (Secure File Transfer Protocol) using Python.

## Features
- **Data Retrieval**: The program retrieves daily sales data from the data warehouse (BigQuery) using SQL queries.
- **Data Summarization**: It summarizes the retrieved sales data based on predefined metrics such as total sales, revenue, and product performance.
- **Custom Formatting**: The summarized data is formatted according to the specific requirements of each mall, ensuring compatibility with their internal systems.
- **Automated Transmission**: The program automatically transmits the formatted data to individual outlet malls' management via SFTP, ensuring timely and secure delivery.

## Installation
To use this program, follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Configure the program settings, including BigQuery credentials and SFTP connection details, in the `config.py` file.
4. Run the program using `python main.py`.

## Usage
1. Specify the date range for which you want to retrieve and summarize sales data.
2. Run the program to initiate data retrieval, summarization, and transmission processes.
3. Monitor the program output for any errors or exceptions.
4. Verify the transmitted data on the SFTP server to ensure successful delivery.

## Example
Below is an example of the summarized sales data format:
![Program Flow](https://github.com/Azeemshah99/Sales_Mall_Submission/blob/main/Flow_Sales_Submission.png)

## Contributors
- John Doe (@johndoe)
- Jane Smith (@janesmith)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
