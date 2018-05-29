##帮你贷相关接口
    
#### @Author: WangYx @Date: 2018/5/28 

###接口： 

| 接口 | 请求方式 | 接口方式 |
| ---  | --- | --- |
| /helploan/apply/reason | POST | 帮你贷用户提交申请理由(需登录) |

###请求参数类型：
| 字段 | 说明 |
| ---  | --- |
| repeatapplyreason ||
| iapplyid ||

###返回值类型
    Result
    
###返回值示例：
    {
        "code":"1",
        "results":{
            .
            .
            .
        },
        "desc":"...",
    }