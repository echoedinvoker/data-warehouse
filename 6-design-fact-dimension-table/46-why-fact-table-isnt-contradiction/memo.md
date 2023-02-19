## **Intro of Factless Fact Table**

![Alt list fact table - final one - factless](pic/01.jpg)

![Alt basic def of factless](pic/02.jpg)

## **Business Question: Student assign webinar**

![Alt business question](pic/03.jpg)

![Alt list of track  (only dimensions)](pic/04.jpg)

![Alt table digram without measurements (facts)](pic/05.jpg)

- So it's not just one to many in accumulating snapshot fact tables, other kinds of tables may also have to use this relationship, and it will happen naturally depending on demand.

### _measurement is row itself_

> The fact table itself must be able to do analysis to be meaningful, but the factless fact table does not have any measurement, so what analysis can be done with it?.

![Alt features of 1st type of factless](pic/06.jpg)

![Alt usage sample 1](pic/07.jpg)

![Alt usage sample 2](pic/08.jpg)

## **Multiple tables to track process of same thing**

### _multiple factless fact tables_

![Alt multiple factless fact tables](pic/09.jpg)

### _combined with transaction table_

![Alt combine with transaction table](pic/10.jpg)

## **Adding Tracking Fact**

> Some people are uncomfortable with all fields being PK-FK pairs, so a field called "tracking fact" has been added to the factless fact table.

![Alt add tracking fact](pic/11.jpg)

![Alt what is tracking fact](pic/12.jpg)

- So using tracking facts is not necessarily a good thing, but at least it is an option.

## **2nd type of Factless Fact table**

> Used to record the fact that there is a association between different departments or people, usually with a start and end date (not mandatory).

![Alt 2nd type of factless fact table](pic/13.jpg)

![Alt digram - how to build fact table](pic/14.jpg)

![Alt thinking](pic/15.jpg)

![Alt build 2nd type of factless fact table](pic/16.jpg)
