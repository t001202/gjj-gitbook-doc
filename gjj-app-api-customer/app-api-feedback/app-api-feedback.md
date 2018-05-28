##公积金反馈系统
    
#### @Author: WangYx @Date: 2018/5/28 

###接口： 

| 接口 | 请求方式 | 接口方式 |
| ---  | --- | --- |
| /feedback | POST | 公积金反馈接口 |
| /v2/feedback | POST | 公积金反馈接口v2 |

###请求参数类型：
####查看用户基本信息重构后接口：
| 字段 | 说明 |
| ---  | --- |
| questionType| 问题类型 |
| questionDescription| 问题描述 |
| MultipartFile| 封装截图 |
| multipartFileList| 截图列表 |

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