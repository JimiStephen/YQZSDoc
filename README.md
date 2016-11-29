# 园区指数接口文档

 utf-8 编码， get 请求 ，返回数据json格式

## 招聘指数

### 招聘指数-主要行业

行业不止一下两个，这为示例

```json
{
  "MainIndustry": {
    "制造业": "123",
    "金融业": "321"
  }
}
```

### 招聘指数-7大类细分行业

GeneralIndustry  一共有7个行业大类

每类去取Top10的细分行业倒序排列

```json
{
  "SubdivideIndustry": {
    "制造业": {
      "飞机制造业1": "23423",
      "骑车制造业2": "111",
      "仪器制造业3": "222"
    },
    "金融业": {
      "银行": "123",
      "保险": "444",
      "证券": "bbb"
    }
  }
}
```





