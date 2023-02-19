## **How to relate between tables**

![Alt fundamental](pic/01.jpg)

## **RDBMS Key Types**

![Alt RDBMS key types](pic/02.jpg)

### _Primary key_

![Alt primary key](pic/03.jpg)

![Alt primay key example](pic/04.jpg)

![Alt primay key example 2](pic/05.jpg)

### _Foreign key_

![Alt foreign key](pic/06.jpg)

![Alt foreign key example 1](pic/07.jpg)

## **Data Warehousing Key Types**

![Alt natural vs surrogate](pic/15.jpg)

### _Natural key_

> A key that is generated from a data source and not from the Data Warehouse is called a natural key.

**Might be cryptic or understandable**

![Alt natural keys (might be cryptic)](pic/08.jpg)

![Alt natural keys (might be understandable)](pic/09.jpg)

**But the point is**

![Alt natural keys travel](pic/10.jpg)

### _Surrogate key_

![Alt best practice: use surrogate key to relate data cross tables](pic/11.jpg)

- Note that the point is to use the surrogate key to relate between different tables, not to say that every table must have a surrogate key.

![Alt surrogate key](pic/12.jpg)

![Alt surrogate key example](pic/13.jpg)

## **Whether to discard the natural key**

> Since it is recommended to use surrogate key to do relate, does the natural key from the data source still need to stay in Data Warehouse?

![Alt data warehousing and natural keys](pic/14.jpg)

