##保险相关接口
    
#### @Author: WangYx @Date: 2018/5/28 

###接口： 

| 接口 | 请求方式 | 接口方式 |
| ---  | --- | --- |
| /insurance/receive | POST | 领取保险 |

###请求参数类型：
| 字段 | 说明 |
| ---  | --- |
| username | 用户姓名 |
| mobileNo | 手机号 |
| idNo | 身份证号码 |
| location | 位置汉字名称，如：首次绑定,贷款H5 |

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