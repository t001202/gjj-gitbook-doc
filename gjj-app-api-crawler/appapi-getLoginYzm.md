##获取验证码接口
    访问频率限定：
        10秒内限定访问6次，若达到这个限制，封禁5分钟
        10秒内限定访问12次，若达到这个限制，封禁10分钟

#### @Author: WangYx @Date: 2018/5/28 

###接口路径：   
 * /user/getLoginYzm.go
 
###请求参数类型
| 字段 | 说明 |
| ---  | --- |
|city,addressCode|城市编码 |
|businessType|业务类型：0：公积金 1：社保  2：车险|
|cuserId|用户ID|

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