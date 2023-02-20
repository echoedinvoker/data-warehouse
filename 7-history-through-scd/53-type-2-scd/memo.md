## **What is Type 2 Slowly Changing Dimension table**

![Alt type2 scd](pic/01.jpg)

![Alt example](pic/02.jpg)

## **The Reasons we use Type 2 Slowly Changing Dimension table**

![Alt reasons](pic/03.jpg)

## **Impact to related Fact table**

![Alt fact table](pic/04.jpg)

![Alt two row fk to same student](pic/05.jpg)

- As shown above, when type 2 SCD generates multiple versions, it also affects the related fact table which also generates multiple rows.

  - This may affect the correctness of our reporting based on these tables.

## **Correct reporting**

### _Bad practice: using natural keys**

![Alt correct reporting 1](pic/06.jpg)

### _Better practice: **careful** 'multi-step' SQL_

![Alt correct reporting 2](pic/07.jpg)

![Alt still](pic/08.jpg)
