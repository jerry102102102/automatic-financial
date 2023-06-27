
## :beginner: Design Info

:::info
Automatic financial protocal.
:::

:small_blue_diamond:Design Name: 自動化理財

:small_blue_diamond:Author: Jerry Chuang

:small_blue_diamond:Status: 
- [x] In progress
- [ ] In review. Reviewer:
- [ ] Finished

## Flow chart
![](https://hackmd.io/_uploads/BJyzFXwu3.png)

## :wrench: Specs

:::success
List the specs you design.
:::

| **Item** | **Spec** | **Note** |
| -------- | -------- | -------- |
|          |          |          |
|          |          |          |

***
:::warning
The following items can make this document more complete.
:::

## :feet: Implementation

* 資料爬蟲
#####  使用twstock package(https://twstock.readthedocs.io/zh_TW/latest/quickstart.html#tpex-twse-codes)
```
import twstock
import time
stocks = []
for keys in stock_list:
    stocks.append(twstock.Stock("2330"))
    time.sleep(3)
```
#####    注意TWSE 5秒只能三個request(相同ip)
* 資料庫維護
* 建立模型
* API自動化交易
* LINE BOT控制

## :blush: Demo
:::success
Show the design and simulation for this product. A good experiment result will ensure an exemplary implementation. You can introduce it here with an image or add a project link.
:::
