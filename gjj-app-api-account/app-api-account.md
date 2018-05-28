##查询Account相关接口

#### @Author: WangYx @Date: 2018/5/28 

###接口路径：   
 * /account/pay/list
 
###请求参数类型
| 字段 | 说明 |
| ---  | --- |
| cityCode | 城市代码 |
| account | 公积金帐号 |
| businessType | 业务类型 |
| gjjType | 公积金类型 0：普通公积金 1：补充公积金 |
| siType | 社保类型(社保备用字段 暂时没用) |
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