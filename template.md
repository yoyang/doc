
### k线服务

**URL**

qoute/dyna

**描述**

动态行情服务

**参数说明**

|名称|类型|说明|缺省|
| -------- | -------- | -------- | -------- |
|obj\*|字符串|查询股票\*表示必填，必填的字段说明放在前面。如SH600000|无|
|field|字符串|字段过滤(见返回说明)|无|

**结果说明**

```json

{
    "Id": 20,
    "RepDataQuoteDynaSingle": [
        {
            "Obj": "SH601519",
            "Data": {
                "Id": 638231067,//说明
                "ShiJian": 369065887036,//时间
                "ZuiXinJia": 970,//最新价
                "KaiPanJia": 890,
                "ZuiGaoJia": 972,
                "ZuiDiJia": 868,
                "ZuoShou": 894,
                "JunJia": 909,
                "ZhangDie": 76,
                "ZhangFu": 850,
                "ZhenFu": 1163,
                "ChengJiaoLiang": 10520025720,
                "XianShou": 704460,
                "ChengJiaoE": 9579555514880,
                "ZongChengJiaoBiShu": 680146,
                "NeiPan": 4850371956,
                "WaiPan": 5671357700
            }
        }
    ]
}
```

**示例**

[/quote/dyna?obj=SH600000]($APIHOST$/quote/dyna?obj=SH600000)