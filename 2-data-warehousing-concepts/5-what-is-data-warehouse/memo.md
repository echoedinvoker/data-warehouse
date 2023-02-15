# ***What is Data Warehouse**

## **Similar to a large warehouse but with data**

![Alt a warehouse ... filled with data](pic/01.jpg)

## **Is it Database?**

![Alt not the same as a database](pic/02.jpg)

![Alt built on top of a database](pic/03.jpg)

## **How or where does the data in it come from?**

![Alt data comes from elsewhere](pic/04.jpg)

- We don't create data for the first time in a data-warehouse.

![Alt possibly dozens of data sources](pic/05.jpg)

![Alt data copied...not moved](pic/07.jpg)

- So the original app system will still keep the data.

# ***Know the RULEs***

## **Who and When build the rules?**

![Alt know the rules](pic/06.jpg)

- In 1990 Inmon introduced a set of rules for data-warehouse.

## **Integrated**

![Alt Bill Inmon, integrated](pic/08.jpg)

- The data-warehouse data comes from many different source systems.

## **Subject oriented**

![Alt subject oriented](pic/09.jpg)

- But no matter how many source systems transfer data to the data-warehouse, the data-warehouse must be subject-oriented.

## **Time variant**

![Alt time variant](pic/10.jpg)

- data-warehouse saves historical data.

## **Non-volatile**

![Alt non volatile](pic/11.jpg)

- The data-warehouse data will only change when refreshing, the data will be stable and unchanged between the last refresh and the next refresh, so that we can do analysis and strategy on the data.

## **Improvement**

![Alt improvement](pic/12.jpg)

- It means that when data is put into the data-warehouse, we usually reorganize it to make it more useful for analysis.

## **Final rule: make decisions**

![Alt why? decision](pic/13.jpg)
