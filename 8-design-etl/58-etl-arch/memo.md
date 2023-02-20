## **Reviews**

![Alt reviews: typical data warehouse env](pic/01.jpg)

![Alt reivews: max-and-match tables level periods](pic/02.jpg)

![Alt reivews: max-and-match tables level method](pic/03.jpg)

## **Main Factors to ETL design**

![Alt main factors to etl design](pic/04.jpg)

## **ETL Best practices and guidelines**

### _Limit amount of incoming data_

![Alt elt best practices and guidelines: limit amount of incoming data](pic/05.jpg)

- We will explain "Change Data Capture" in other lectures.

- We only need subsets of data from data sources, those that are not in the data warehouse or that need to be updated.

### _Order by dependent relations (dimention tables -> fact tables)_

![Alt elt best practices and guidelines: dependent](pic/06.jpg)

- Because surrogate key is generated in dimension table, so the order is important (point is surrogate key).

### _Better do parrallel processing_

![Alt elt best practices and guidelines: parrallel better 1](pic/07.jpg)

![Alt elt best practices and guidelines: parrallel better 2](pic/08.jpg)

## **Our Focus**

![Alt our focus](pic/09.jpg)

- In the following lectures, we will focus on the ETL design of the red circles, if you know these parts, you should be able to figure out the other parts by yourself.
