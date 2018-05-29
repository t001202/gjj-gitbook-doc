##帮你贷相关接口
    
#### @Author: WangYx @Date: 2018/5/28 

###接口： 

| 接口 | 请求方式 | 接口方式 |
| ---  | --- | --- |
| /helploan/apply/loansimple | POST | 帮你贷添加简单信息(需登录) |

###请求参数类型：
| 字段 | 说明 |
| ---  | --- |
| LoanSimpleDto |实体类|

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