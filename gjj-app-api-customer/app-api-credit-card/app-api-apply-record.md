##获取申请的信用卡列表
    
#### @Author: WangYx @Date: 2018/5/28 

###接口路径：   
 * /credit
 
###请求方式：
*POST

###请求参数类型
| 字段 | 说明 |
| ---  | --- |
| productId| 产品ID |
| account| 公积金账号 |
| cityCode| 城市编码 |
| realName| 真实姓名 |
| cardNo| 身份证号 |
| mobileNo| 手机号 |

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