##登陆接口
    
#### @Author: WangYx @Date: 2018/5/28 

###接口： 

| 接口 | 请求方式 | 接口方式 |
| ---  | --- | --- |
| /login | POST | 公积金反馈接口 |

###请求参数类型：
####查看用户基本信息重构后接口：
| 字段 | 说明 |
| ---  | --- |
| username| 用户名 |
| password| 登录密码 |
| source| source值 |
| mobileType| 手机系统类型(0:iOS,1:ANDROID) |
| signMsg| --- |
| version| 版本号 |

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