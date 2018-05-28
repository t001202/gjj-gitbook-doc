##我的消息接口
    
#### @Author: WangYx @Date: 2018/5/28 

###接口： 

| 接口 | 请求方式 | 接口方式 |
| ---  | --- | --- |
| /message | POST | 我的消息接口 |
| /v2/message | POST | 我的消息接口 |

###请求参数类型：
####查看用户基本信息重构后接口：
| 字段 | 说明 |
| ---  | --- |
| source| source值 |
| messageType| 0代表资讯通知，1代表限时福利 |
| devType| 设备类型 |
| rows| --- |
| page| --- |

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