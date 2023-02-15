## **Centralized vs Component-Based**

![Alt first decision: central - good](pic/01.jpg)

![Alt first decision: central - bad](pic/02.jpg)

![Alt first decision: component - good](pic/03.jpg)

![Alt first decision: component - bad](pic/04.jpg)

- Although it seems that Component-Based has more advantages and fewer disadvantages, remember that the default option is still 'Centralized'.

## **Centralized - EDW vs Data Lake**

![Alt EDW vs Data Lake](pic/05.jpg)

- The 'E' in EDW is Enterprise.

- As mentioned in the previous lecture, we see Data Lake as the successor to the classic Data Warehouse, so it makes sense to put it here.

### _EDW branches_

![Alt EDW branches](pic/06.jpg)

- Specialized Database is a database designed specifically for EDW.

### _Data Lake branches_

![Alt DataLake branches](pic/07.jpg)

## **Component-Based - Architected vs Non-Architected**

> Whenever Data Marts are used, it is considered Component-Based.

![Alt compoenent branches](pic/08.jpg)

- Specialized Database can also be used as a platform for Data Lake.

### _Architected - DW+DMs vs DMs Only_

![Alt arch branches](pic/09.jpg)

- Basically, this section is for solving cross-departmental communication problems within the organization.

**DW+DMs**

![Alt DW+DMs - dependent DMs](pic/10.jpg)

- Already explained with the analogy with retailers in previous lectures.

- There is a variation of the dependent data mart, it is called the Corporate Information Factory, or CIF.

  - CIF is proposed by Inmon, in fact, it is Data mart with a series of specifications.

  - If you use CIF, it is easy to find the information and data you need.

  - Nowadays, less people use it.

![Alt DW+DMs - Front-End DMs](pic/11.jpg)

- For example, if the same SAP company has both foreign and domestic companies, you can use two Data Mart to integrate the foreign data with the domestic data.
  
  - Most of the analysis and reporting will be done directly in the Data Mart section.

  - But in the end, all the data will be aggregated in the Data Warehouse.

**DMs Only**

![Alt DMs Only - DW Bus](pic/12.jpg)

- It's called the data warehouse dimensional bus that was defined by Ralph Kimball.

- The idea behind the data warehouse bus is that all of the data marts follow a principle that known as **confirmed dimensions**.

  - means that we have an **apples to apples view** about our key subject areas.

    - key subject areas such as customers, products, employees ...

### _Non-Architected_

![Alt non-arch - federated EDW](pic/13.jpg)

- Each department uses its own data mart to make its own suggestion for decisions.

  - Each suggestion does not need to be the same.

## **Overview**

![Alt overview](pic/14.jpg)
