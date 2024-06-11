# tokyo-olympic-azure-data-project
End to end data project using tokyo olympic data

## Description:
This project provides a data engineering and anlytical journey on the Tokyo Olympic dataset. Starting with a CSV on GitHub, the data is ingested into the Azure ecosystem via Azure Data Factory. It's initially stored in Azure Data Lake Storage Gen2, then transformed in Azure Databricks. The enriched data, once again housed in ADLS Gen2, undergoes advanced analytics in Azure Synapse. The insights are finally visualized in Azure Synapse or Power BI, offering a comprehensive view of the dataset.

## Architecture
![Architecture](https://github.com/yaminitulabandula/tokyo-olympic-azure-data-project/assets/113737709/bafcc308-929f-4800-a5b6-6070b0541276)

## Dataset Used
This contains the details of over 11,000 athletes, with 47 disciplines, along with 743 Teams taking part in the 2021(2020) Tokyo Olympics. This dataset contains the details of the Athletes, Coaches, Teams participating as well as the Entries by gender. It contains their names, countries represented, discipline, gender of competitors, name of the coaches.

Source(Kaggle): 2021 Olympics in Tokyo (https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)
