## **Two Layers inside Data Warehouse**

![Alt look inside dw](pic/01.jpg)

### _Staging Layer_

![Alt staging layer](pic/02.jpg)

### _User Access Layer_

![Alt user access layer](pic/03.jpg)

- We have often heard of snowflake patterns, dimension tables, fact tables, etc. being constructed in this layer.

![Alt overview pic](pic/04.jpg)

## **What kind of tables in Staging Layer**

![Alt similar table](pic/05.jpg)

- In order to copy the data to the staging area as quickly as possible, we create tables with similar structure to the data source.

![Alt one to one](pic/06.jpg)

![Alt combine to user access layer](pic/07.jpg)

- Even though different data sources have similar structures, we still prefer to use a one-to-one mapping method and merge only at the user access layer.

![Alt many to one](pic/08.jpg)

![Alt if data is uniform](pic/09.jpg)

- It is not impossible to implement many-to-one method, but need to ensure that the data is uniform, but in reality, the format of different data sources is usually not uniform.

## **ETL from Data source to staging layer**

![Alt ETL focus on E and minus T](pic/10.jpg)
