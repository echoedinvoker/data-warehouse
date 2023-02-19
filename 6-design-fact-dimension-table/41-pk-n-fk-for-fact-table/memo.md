## **How to generate Primary Key of Fact table**

![Alt fk in fact table to surrogate keys in dimension tables](pic/01.jpg)

- The above diagram is borrowed from the table diagram of the previous lecture.

- Because the fact table on the left is a two-dimensional grain, there are two foreign keys that relate to the two dimension tables.

![Alt group fk to primary key of fact table](pic/02.jpg)

- In the fact table, we use all foreign keys to form a unique primary key.

  - Each foreign key is a surrogate key in the other dimension table.

## **Annotations in Table Diagram**

![Alt annotations in table diagram](pic/03.jpg)

## **Natural keys with Facts**

![Alt source may have key for fact](pic/04.jpg)

![Alt natural key in fact table](pic/05.jpg)
