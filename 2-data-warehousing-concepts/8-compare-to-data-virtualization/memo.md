## **History**

### _1980s-era Extract files_

![Alt 1980s-era extract files](pic/02.jpg)

- extract files is like a mini data warehouse that extracts data from one or more applications, but without any coordination and rules of data structure, and almost without any part beyond extraction.
  - As a result, the time spent collecting and reconstructing data over and over again is still much more than the time spent actually analyzing the data.

### _late 1980: Distributed DBMS_

![Alt late 1980: distributed dbms (DDBMS)](pic/03.jpg)

- Distributed data management system regardless of the degree of distribution, index will go to each place to extract the correct data and then organize it.

- The concept was solid, but it failed because of the lack of technology at the time.

### _After DDBMs fail_

![Alt DDBMSs to](pic/05.jpg)

- The failure of DDBMSs led to the creation of Data Warehouse and Data Virtualization.

## **Features fo Data Virtualization**

### _Read only DDBMS_

![Alt Data Virtualization: read-only DDBMS](pic/06.jpg)

### _In-place data access_

![Alt Data Virtualization: In-place data access](pic/07.jpg)

- It means that it does not duplicate data.

### _Many names over the years_

![Alt Data Virtualization: Many names over the years](pic/08.jpg)

- Such as:

  - Virtual Data Warehouse

  - Enterprise Information Integration (EII)

  - Enterprice Data Access (EDA)

## **Significantly Improved from the late 1980s and early 1990**

![Alt niche](pic/09.jpg)

- That said, it is best to use Data Virtualization only in the following use cases:

### _Simple or no transformation_

![Alt Data Virtualization use cases: simple transformations](pic/10.jpg)

### _Smaller number of data sources_

![Alt Data Virtualization use cases: smaller number of data sources](pic/11.jpg)

### _Relaxed response time_

![Alt Data Virtualization use cases: relaxed reseponse time](pic/12.jpg)

## **Combined All tools to provide BEST VALUE**

![Alt BEST VALUE](pic/13.jpg)
