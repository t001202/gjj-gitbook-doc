##保险相关接口
    
#### @Author: WangYx @Date: 2018/5/28 

###接口： 

| 接口 | 请求方式 | 接口方式 |
| ---  | --- | --- |
| /insurance/firstbinding | POST/GET | 明细页首次绑定保险领取校验接口 |

###请求参数类型：
| 字段 | 说明 |
| ---  | --- |
| username | 用户姓名 |
| mobileNo | 手机号 |
| idNo | 身份证号码 |
| bussinessType | 业务类型0：公积金，1：社保 |

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