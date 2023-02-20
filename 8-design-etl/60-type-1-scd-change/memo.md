## **Follow ETL Steps**

![Alt follow ETL steps to step 4](pic/01.jpg)

- It is best to follow the ETL steps, step by step to get to this stage.

## **Reviews Basic correcting error with Type 1 SCD**

![Alt review: basic correcting errors with type 1 scd 1](pic/02.jpg)

![Alt review: basic correcting errors with type 1 scd 2](pic/03.jpg)

- In the previous lecture, the above example was explained in a simple SQL update syntax, but in fact there are more complicated cases.

## **Where the Type 1 SCD become complicated and solution**

![Alt where type 1 scd become complicated](pic/04.jpg)

- Although the Type 2 SCD change should be executed in the next stage according to the steps sequence, it is possible that the Type 2 SCD was executed in the previous ETL, so this situation may happen.

![Alt example of multiple row need to be correct 1](pic/05.jpg)

![Alt example of multiple row need to be correct 2](pic/06.jpg)

- So when using Type 2 SCD, we use the natural key to search for rows that need to be updated instead of the primary key.

  - So natural key is very important in Dimension table, not just keep it.
