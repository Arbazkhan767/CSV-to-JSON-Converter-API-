# CSV-to-JSON-Converter-API-
In this project, the aim is to build a robust API that converts CSV files into JSON data structures and efficiently stores them in a PostgreSQL database. The API is developed using Express.js, providing a flexible and user-friendly interface for handling large volumes of CSV data.


API.js:-

![image](https://github.com/Arbazkhan767/CSV-to-JSON-Converter-API-/assets/68524549/b31abb97-adda-4ded-b429-1b7129ab9710)

The API will accept CSV files as input, with each row in the CSV representing a distinct object. The CSV file will include fields, and complex properties will be denoted using dot (.) separators. Mandatory properties, such as name.firstName, name.lastName, and age, will be specified at the beginning of each record. The API will parse the CSV file and convert it into a list of JSON objects. Complex properties will be structured accordingly within the JSON objects.

JSON Output:-
![image](https://github.com/Arbazkhan767/CSV-to-JSON-Converter-API-/assets/68524549/6de2ac7d-e8e2-4365-8ab9-b25eda26ce8e)


POSTGRES Output:-
![image](https://github.com/Arbazkhan767/CSV-to-JSON-Converter-API-/assets/68524549/e731441d-a925-408f-8b8c-9de716f22ec2)

The API will connect to a PostgreSQL database to store the converted JSON data.

Mandatory properties will be mapped to designated fields, while additional properties will be stored in the additional_info field as a JSON object. Scalability and Performance:

The API is designed to handle large CSV files efficiently, supporting potentially over 50,000 records. It implements data processing optimizations to minimize resource consumption during conversion and database insertion.

Age Distribution Report:
![image](https://github.com/Arbazkhan767/CSV-to-JSON-Converter-API-/assets/68524549/2c807ffc-1f4a-4520-b714-3664f915c609)

After successfully uploading records to the PostgreSQL database, the API will calculate the age distribution of all users. It will generate a detailed report and print it to the console. The report will display the age groups and their corresponding percentage distribution, helping stakeholders gain insights into the user demographics.

Config:-
![image](https://github.com/Arbazkhan767/CSV-to-JSON-Converter-API-/assets/68524549/011f33c7-4752-47a2-ba30-7d19e81cbcd6)

The API will provide a configuration mechanism, allowing users to define the location of CSV files. Configuration file is used for flexibility in specifying file paths and database connection details.
