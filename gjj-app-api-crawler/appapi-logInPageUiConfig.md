##公积金登录配置文件

#### @Author: WangYx @Date: 2018/5/28 

###接口路径：   
 * /gjj/logInPageUiConfig.go
 
###请求参数类型
| 字段 | 说明 |
| ---  | --- |
|addressCode|城市编码 |
|businessType|业务类型：0：公积金 1：社保  2：车险|
|version|版本号|

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