# Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_Spotify_Music_Database

## Purpose

The primary purpose of this ETL pipeline is to reinforce the foundational data principles acquired through self-study, my master's program and practical internship experience. Drawing on the knowledge and skills developed, the project aims to apply these principles to the real-world scenario of building a music database. By extracting, transforming, and loading data from Spotify's API, the pipeline serves as a hands-on application of data management concepts. This project is a steppingstone to solidify my understanding of data processing, analytics, and storage.

## Scope and Goals

The scope of the project encompasses the end-to-end process of constructing a music database, starting from the extraction of artist data from Spotify, including details like discography, albums, songs, followers, and genres. The goal is not only to create a functional ETL pipeline but also to deepen my understanding of Microsoft Azure, a key technology in the contemporary data landscape. Achieving this involves successfully implementing and optimizing the data pipeline, incorporating Azure services as needed. The overarching objective is to gain practical expertise in designing, building, and maintaining an effective data pipeline, contributing to my overall proficiency in the realm of data engineering and analytics.

## Tools and Technologies Used

### 1. List of Technologies
Azure Data Factory: For orchestrating workflows
Azure Dataflows: For efficient data transformations
Azure Databricks: For advanced processing capabilities
Azure SQL: For detailed analysis, utilizing Azure's relational database service
Tableau: For visualizing and reporting insights
Python scripting: For specific functionalities

### 2. Justification for Selecting Each Tool
My decision to exclusively utilize Azure services stems from a deeply personal motivation – the pursuit of the Azure Data Engineering Associate certification. By immersing myself in Azure Data Factory, Dataflows, Databricks, and SQL, I ensure seamless integration within the Azure environment. This strategic choice aligns with the specific objectives of the certification, contributing not only to a comprehensive understanding of Azure's data services but also to the practical application of this knowledge within a real-world project.

## Architecture Diagram

The architecture diagram illustrates the flow and integration of various components in the ETL pipeline.

ER Diagram
![image](https://github.com/SyakeerRahman/Data_Engineer_Project_An_End_to_End_Azure_Data_Engineering_Spotify_Music_Database/assets/105381652/078c56d4-acfb-410d-91af-5db80e8f404e)

The ER diagram showcases the relationships between different entities in the music database schema.

Before running the ETL pipeline, make sure you have the necessary dependencies installed. You can install them using the following commands:

```ruby
pip install spotipy  # Python library for Spotify API
```ruby
