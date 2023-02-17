## **What is incremental ETL**

> After the initial ETL is used to get the Data Warehouse up and running, the subsequent ETLs are incremental ETLs, designed to get the Data Warehouse up to date.

### _Features_

![Alt what is incremental etl](pic/01.jpg)

### _Main purpose_

![Alt key](pic/02.jpg)

## **For kinds of incremental ETL**

> There are four types of incremental ETL depending on the type of method used to get the data up to date.

![Alt append](pic/03.jpg)

![Alt in-place update](pic/04.jpg)

- Change the value of existing rows, so the overall number of rows will not change.

![Alt complete replace](pic/05.jpg)

![Alt rolling append](pic/06.jpg)

- The data is added in the same way as append, but the data is kept for a certain period of time, and the old data is deleted when append.

## **Today**

![Alt today](pic/07.jpg)
