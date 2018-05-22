# mm-sku

> SKU选择器 - 小程序组件

## Install

``` bash
$ min install @qianzhaoy/mm-sku
```


## API

### Sku


| 名称                   | 描述                 |  类型  |  默认值  |
|:---: |:--------: |:--------:| :---: |
|`sku`                   | 商品sku数据          | Object | --  |
|`goodsId`               | 商品id               | Number | null |
|`goods`                 | 商品信息	            | Object | -- |
|`quota`                 | 限购数(0表示不限购)	 | Number | 0 |
|`quotaUsed`             | 已经购买过的数量      | Number | 0 |
|`showAddCartBtn`        | 是否显示加入购物车按钮 | Boolean | false |
|`buyText`               | 购买按钮文本          | String | 立即购买 |

Event

| 事件名       | 说明               |  参数  |
| :--------:   | :-----:   | :----: |
| add-cart |  点击添加购物车回调 |  skuData: Object |
| buy-clicked | 点击购买回调	|  skuData: Object |
| error | 未选择完整规格值时点击确定的错误	|  errorMsg: String |

## ChangeLog

#### v1.0.0（2018-5-22）

- 初始版本
