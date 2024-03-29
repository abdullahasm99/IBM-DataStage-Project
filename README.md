# Retail Data ETL Solution

## Overview

This project entails the development of an ETL (Extract, Transform, Load) solution tailored for retail data processing and analysis. The aim is to translate logical data models into physical data models, load sample data, and utilize an ETL tool to extract, transform, and load data into files or databases based on business requirements. The project also includes the creation of data marts and analysis of sales data to address specific business needs.

## Project Requirements

1. **Logical to Physical Data Model Translation**: The initial step involves translating the logical data model into a physical data model. This step has been completed, and samples of the loaded data files are available.

2. **ETL Solution Development**: Using an ETL tool, the project aims to create a solution to load data into files or databases as per business needs. The source data is processed through transformations to meet specific business requirements.

## Business Needs Addressed

### Retail Data Mart Creation
- **Objective**: Create a data mart named "RETAIL_DATA_MART" to display each transaction for each customer based on their type (citizen or foreign), including product information and stock details. All customer names should be transformed to uppercase.

![image](https://github.com/abdullahasm99/IBM-DataStage-Project/assets/153215733/21fc46d6-70ac-47f6-abb0-f80e2d419e96)


### Activation Sales Data Mart Analysis
- **Objective**: Analyze the "ACTIVATIONSALES_DATA_MART" to address the following business needs:
    - Display the count of all transactions for each employee in each store.
    - Determine the customer type (citizen or foreign) that has made the maximum profit. The profit calculation is based on the number of transactions made by each customer type.

 ![image](https://github.com/abdullahasm99/IBM-DataStage-Project/assets/153215733/dbfd3602-32dd-4424-827c-259d1228c6d3)


## License

This project is licensed under the [MIT License](LICENSE).
