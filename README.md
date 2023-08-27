# PySpark MongoDB Data Reading Script

## Description

This Python script demonstrates how to read data from a MongoDB collection using PySpark and load it into a Spark DataFrame. The script creates a Spark session, configures the MongoDB input URI, loads data from MongoDB into a DataFrame, displays the content, and then stops the Spark session.

## Table of Contents
- [Description](#description)
- [Usage](#usage)
- [Prerequisites](#prerequisites)
- [Running the Script](#running-the-script)
- [License](#license)
- [Contact](#contact)

## Usage

This script provides a basic example of reading data from a MongoDB collection using PySpark. You can use it as a starting point for more complex data processing tasks involving MongoDB and Spark.

## Prerequisites

Before running the script, make sure you have the following:

- [PySpark](https://pypi.org/project/pyspark/): Install using `pip install pyspark`.
- [MongoDB Spark Connector](https://docs.mongodb.com/spark-connector/master/): Download and include the connector JAR in your project.

## Running the Script

1. Clone this repository or create a new directory for your project.
2. Download and include the MongoDB Spark Connector JAR in your project.
3. Modify the MongoDB URI in the script (`spark.mongodb.input.uri`) to point to your desired database and collection.
4. Open a terminal or command prompt and navigate to the directory containing the script.
5. Run the script using `spark-submit`:
   ```shell
   spark-submit read_mongodb.py
