# 贷款产品详情页

/notcontrol/youyu/loan/loanProductDetail.go

#### 接口编写：姜浩

## 测试链接：

[http://192.168.1.51:10110/notcontrol/youyuloan/loan/loanProductDetail.go?loanProductId=6](http://192.168.1.51:10110/notcontrol/youyuloan/loan/loanProductDetail.go?cuserId=test1&loanProductId=6)

## 请求参数：公共参数

| 字段 | 说明 |
| --- | --- |
| loanProductId | 贷款产品id |

## 返回值说明：

| 字段 | 说明 |
| --- | --- |
| loanProductId | 贷款产品id |
| realProductId | 贷款产品实际id |
| loanQuotaLow | 贷款最低额度 |
| loanQuotaHigh | 贷款最高额度 |
| loanQuotaType | 贷款额度类型 1：元 2：万元 |
| quotaRange | 递增额度 |
| loanTermLow | 最低贷款期限 |
| loanTermHigh | 最高贷款期限 |
| loanTermType | 贷款期限类型 1：天，2：月 |
| loanRate | 费率%\(数据为百分号前0.x\) |
| loanRateUnit | 费率类型 1：日费率 2：月费率 |
| loanRateDesc | 利率说明 |
| loanStatus | 申请状态:0 立刻申请1 补充资料 |
| authenticStatus | 认证状态  0未认证， 1认证中， 2已认证， 3有错误信息 |
| authenticType | 需要认证的类型 0基本信息 1手机运营商 2补充信息 3芝麻信用 4淘宝认证 |
| errorDesc | 错误信息 |
| errorInfo | 描述的信息 |

## 返回值示例：

```
{
  "code": "1",
  "data": {
    "loanQuotaLow": 1000,
    "loanTermHigh": 24,
    "authenticInfo": [
      {
        "authenticStatus": "3",
        "errorDesc": "用户名与基本信息囧雪不符，请保证准确一致",
        "errorInfo": "囧恩|姓名不符",
        "authenticType": "0"
      },
      {
        "authenticStatus": "1",
        "authenticType": "1"
      },
      {
        "authenticStatus": 1,
        "authenticType": "2"
      },
      {
        "authenticStatus": "1",
        "authenticType": "3"
      }
    ],
    "loanTermType": 1,
    "loanRateUnit": 1,
    "loanRateDesc": "利率说明",
    "loanStatus": 1,
    "loanTermLow": 12,
    "loanQuotaHigh": 20000,
    "loanQuotaType": 1,
    "quotaRange": 1000,
    "loanRate": 0.22,
    "loanProductId": 6,
    "realProductId": "APPID2"
  },
  "desc": "查询贷款详情完成",
  "success": true
}
```



