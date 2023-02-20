# ***CREATE TABLE Examples***

> Next, we will write SQL script using various types of table concept diagrams, so that we can have some understanding in the practical part.

![Alt create table examples for](pic/01.jpg)

## **Dimension table**

### _Star Schema_

![Alt star schema dimension table](pic/02.jpg)

### _Snowflake Schema_

**Non-terminal table**

![Alt snowflake schema non-terminal dimension table](pic/03.jpg)

**Terminal table**

![Alt snowflake schema terminal dimension table](pic/04.jpg)

## **Fact table**

### _Transaction-Grained Fact table_

**Primary key**

![Alt transaction-grained fact table pk](pic/05.jpg)

**Foreign key**

![Alt transaction-grained fact table fk](pic/06.jpg)

### _Periodic Snapshot Fact table_

![Alt periodic snapshot fact table](pic/07.jpg)

### _Others_

- Should have accumulating snapshot fact table and factless fact table, but the course does not include this part of the example.

- The accumulating table will have to relate to the same dimension table, so the foreign key name will not be the same as the primary key name of the dimension table.

- The factless fact table part will have no measurement column, or only tracking fact, which should be using the boolean type.
