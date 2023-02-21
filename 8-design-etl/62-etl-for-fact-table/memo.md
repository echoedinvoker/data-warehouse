## **Before ETL to Fact table**

![Alt after process dimension tables](pic/01.jpg)

![Alt use previous sample](pic/03.jpg)

![Alt before ETL](pic/04.jpg)

## **ETL of Fact table**

![Alt included in next incremental ETL](pic/05.jpg)

### _Multiple records in dimension table_

![Alt after type 2 change in student dim table](pic/07.jpg)

**pick current_flag = Y**

![Alt just pick current_flag = true](pic/09.jpg)

**use relevant date to filter**

![Alt use relevant date to filter](pic/11.jpg)

![Alt get surr key to fact table](pic/12.jpg)

> If you use the relevant date, you can insert historical fact information, which cannot be done by using current_flag alone.

![Alt in case of history fact](pic/13.jpg)

![Alt get surr key of old version to fact table](pic/14.jpg)

## **Watch for Complications...**

![Alt watch for complications](pic/15.jpg)

- While inserting or updating a single table may feel simple, but linking different tables together can produce complex results.

  - If you are not prepared for the complexity you will face, the result will be very difficult to manage.
