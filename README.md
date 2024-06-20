# Mall-Customer-Segmentation-Data

**Context**
Synthetic Dataset of Customer Transactions with Demographic and Shopping Behavior Information. I will demonstrate this by using unsupervised ML technique (KMeans Clustering Algorithm) in the simplest form.

**Features**
Customer ID: The unique identifier for each customer.
Name: The customer's name.
Surname: The customer's last name.
Gender: The gender of the customer.
Birthdate: The customer's date of birth.
Transaction Amount: The amount of the transaction. ($)
Date: The date of the transaction.
Merchant Name: The name of the merchant where the transaction was made.
Category: The category of the transaction.

**Problem Statement**
You have been asked by your Data Insight Manager to analyze the transaction data from the CRM, to fully understand the various customers and their transactions. You will be expected to provide insights into spending habits and seasons to both marketing and sales teams. You can also create a dashboard and report to help the various stakeholders understand your finding and make insightful decisions.

**Steps**
*Exploratory Data Analysis*
All missing values on the "Gender" column are replaced with the most frequent gender in that column.
*Feature Engineering*
1. New features created
   *BirthYear*
   *Month*
   *PurchaseMonth*
   *Generation*
   *Season*
   *Age*

![Screenshot 2024-06-20 141114](https://github.com/uzeziogho/Customer-Segmentation/assets/58593651/1c56ceb5-c8d5-4385-bb64-837e56b073bf)

2. Pick the most efficient cluster using Elbow Method

![Screenshot 2024-06-20 141142](https://github.com/uzeziogho/Customer-Segmentation/assets/58593651/010c8b15-dc3c-451b-8954-4a90952ea85b)

3. Confirm using Silhouette method

![Screenshot 2024-06-20 141157](https://github.com/uzeziogho/Customer-Segmentation/assets/58593651/960eade2-1d8e-42af-a292-4fec7ace8f77)

4. Visualise clusters using Barchart

![Screenshot 2024-06-20 141216](https://github.com/uzeziogho/Customer-Segmentation/assets/58593651/ce0a6dd9-7282-44b4-8ad7-b76f1e6ba8e3)

5. Create a new "cluster" column using pandas

![Screenshot 2024-06-20 141440](https://github.com/uzeziogho/Customer-Segmentation/assets/58593651/63b40848-5645-4a7c-ad7c-7f2278003adf)

6. Export the new table as a .csv file to PowerBI

<img width="662" alt="Screenshot 2024-06-20 140834" src="https://github.com/uzeziogho/Customer-Segmentation/assets/58593651/044f9e17-4d0f-4c14-b4fc-c53ef99c8f77">
