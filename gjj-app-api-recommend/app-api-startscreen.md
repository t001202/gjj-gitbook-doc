##推荐位接口
    
#### @Author: WangYx @Date: 2018/5/30 

###接口： 

| 接口 | 请求方式 | 接口方式 |
| ---  | --- | --- |
| /recommend/start/screen | GET | 启动全屏广告位接口 |

###请求参数类型：
| 字段 | 说明 |
| ---  | --- |
| packageType |  |
| width |  |
| height |  |
| existenceType | 数据类型：1：正式数据 0：审核数据，默认值：1 |

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