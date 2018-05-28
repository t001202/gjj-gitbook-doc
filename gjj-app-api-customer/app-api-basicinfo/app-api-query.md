##查看用户基本信息接口
    
#### @Author: WangYx @Date: 2018/5/28 

###接口： 

| 接口 | 请求方式 | 接口方式 |
| ---  | --- | --- |
| /basic/info| GET | 查看用户基本信息接口 |
| /basic/info| POST | 添加、编辑用户基本信息接口 |
| /basic/v2/info| POST | 查看用户基本信息重构后接口 |
| /basic/info/userbasicinfo | POST | 添加、编辑用户基本信息新接口 |


###请求参数类型：
####查看用户基本信息重构后接口：
| 字段 | 说明 |
| ---  | --- |
| GjjBasicInfoRequest| 用户信息实体类 |
| basicInfo| 用户信息实体类的字符串 |

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