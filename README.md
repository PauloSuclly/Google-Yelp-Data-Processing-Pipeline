# **Data Processing**

One of the most important things on this project is the treatment and organization of the data. The following shows the data processing scheme. 

<img src="./_src/Data_Warehouse.png" alt="Data Warehouse Process">

## Parts of the Process
[Data Lake](#Data-Lake)
</br>

[Technologies](#Technologies)

## Data Lake

The beginning part of this project is to upload raw data that was given to us and store it into our Data Lake.
</br>
**What is a Data Lake ?**
</br>
A Data Lake is a data storage system that allows large amounts of data to be stored in its native format, without the need for prior structuring, allowing faster and more flexible access to data. We are going to use Google Cloud Storage to store the raw data of Google & Yelp.
</br>
**Why Google Cloud Storage ?**
</br>
We choosed Google Cloud Services in general, because they have an amazing UI, very easy to use and very complete. Also and important fact is their competitive prices, We found no reason to don't Google Cloud Services.
</br>

<p align=center><img src="./_src/Data_Lake_Screenshot.png" alt="Data Lake"></p>


## Cloud Functions

We used Google Cloud Functions for the task of extracting the data from the Data lake, transforming/cleaning it and loading it in our Data Warehouse, which will be explained in detail later.
</br>

<p align=center><img src="./_src/Cloud_Functions.png" alt="Cloud Functions"></p>

## Data Warehouse

After cleaning the data and making all the transformations

</br>

<p align=center><img src="./_src/Data_Warehouse_Screenshot.png" alt="Data Warehouse"></p>

## Technologies

* Google Cloud Plataform (GCP)
* Google Cloud Storage
* Google Cloud Function
* Google Big Query
* Pandas
* Python




