## Project Introduction:
There is nothing more boring than having to repeat the same steps of data load and store every day. Well, now no more!\
With the help of this exciting Microsoft Azure project, I intend to automate the tasks of loading vehicle data from the Amazon Web Services S3 storage to Azure Data Lake Gen 2 Storage using Azure Data Factory. That data will then be processed and stored to either Staging or Rejected folders based on its formation. Then from Data Lake Gen 2 Storage staging folder, that data will finally be stored in SQL Database Table. This process will be carried out daily, each data file separated based on date and months.
## Technologies Used:
i.	Amazon Web Services S3 storage\
ii.	Azure Data Factory\
iii.	Azure Data Late Gen 2 Storage\
iv.	Azure Key Vault\
v.	Azure Function\
vi.	Azure SQL Database
## Project Stages:
1-	AWS S3 to Azure Data Lake Gen 2 Storage:
In this stage, we copy data files from AWS S3 to Data Lake Gen 2 Storage using Data Factory Pipeline. For the purposes of security, Azure Key Vault was used to store access keys as a secret.\
2-	Azure Function to Clean the Data:
Azure function was used to decide whether the incoming data should be stored in Staging folder or rejected folder. The function has 1 input and 2 outputs.\
3-	Data Lake Gen 2 Storage to Azure SQL Database:
When the data is stored to Data Lake Gen 2 Storage staging folder, it is then stored as SQL table in SQL database using data factory.
## Project Outcomes:
This project allowed me to demonstrate my expertise in Azure technologies, particularly in using Azure Data Factory to orchestrate complex data workflows. The integration with AWS S3 and Azure Data Lake Gen 2 further showcased my ability to work with multiple platforms and cloud providers.\
I'm excited to continue honing my skills and exploring the endless possibilities that the Azure ecosystem has to offer. If you're interested in learning more about this project or collaborating on similar projects, feel free to reach out to me!
