## **Step-by-step procedure for Non-Persistent Staging Layer**

![Alt no-persist 1](pic/01.jpg)

![Alt no-persist 2](pic/02.jpg)

![Alt no-persist 3](pic/03.jpg)

![Alt no-persist 4](pic/04.jpg)

- Because the user does not access any data from the staging layer, emptying this layer will not have any effect.

![Alt no-persist next round](pic/05.jpg)

- The staging layer remains empty the next time new data comes in.

## **Step-by-step procedure for Persistent Staging Layer**

![Alt persist 1](pic/09.jpg)

- There is already data in it before it is even used.

![Alt persist 2](pic/10.jpg)

![Alt persist 3](pic/11.jpg)

![Alt persist next round](pic/12.jpg)

## **Advantages and Disadvantages**

### _Non-persistent_

![Alt non-persist adv and disadv](pic/15.jpg)

- Once the user access layer is destroyed and needs to be reorganized, the data must be collected from the data source again.

- QA means data quality assurance, when they have a need to compare data, they must also go to the data source for.

### _Persistent_

![Alt persist adv and disadv](pic/16.jpg)

- Rebuilding the user access layer is easy, because the staging layer has all the data, same as QA problem.

- Of course, it goes without saying that a lot of storage space is obviously needed.

- Another point is that staging with a lot of data, which is a risk in itself.
