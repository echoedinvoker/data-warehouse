## **Fundational Concepts(reviews)**

![Alt fundational concepts](pic/01.jpg)

## **Keys of Dimension tables**

![Alt representative dimensions](pic/02.jpg)

- We will then use the two classic dimensions examples above as examples.

![Alt columns (fields) of faculty_DIM](pic/03.jpg)

![Alt columns (fields) of faculty_DIM add surrogate key](pic/04.jpg)

- As mentioned in the previous lecture, the best way is to use surrogate key to relate talbes, so we will add a field "XXX_Key" as surrogate key and also as primary key.

![Alt columns (fields) of student_DIM add surrogate key](pic/05.jpg)

## **Other concepts of Dimension tables**

### _Concept of Dimension talbes_

![Alt dimension tables](pic/06.jpg)

### _Hierarchical vs Flat dimensions_

![Alt hierarchical vs flat dimensions](pic/07.jpg)

## **Star and Snowflake Schemas**

### _Star Schema_

![Alt star schema](pic/08.jpg)

### _Snowflake schema_

![Alt snowflake schema](pic/09.jpg)

![Alt sknowflake schema PK-FK rules - non-terminal](pic/10.jpg)

![Alt sknowflake schema PK-FK rules - terminal](pic/11.jpg)

## **Snowflake hierarchy with Branching**

> Sometimes the dimension table itself can be described by more than one dimension, which results in branches as follows.

![Alt snowflake hierarchy with branching](pic/12.jpg)

![Alt branching: primary and foreign keys](pic/13.jpg)
