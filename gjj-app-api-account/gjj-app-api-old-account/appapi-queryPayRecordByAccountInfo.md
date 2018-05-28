##根据帐号基本信息查询公积金社保明细
###接口路径：   
 * /user/queryPayRecordByAccountInfo.go
 
###请求参数类型 
| 字段 | 说明 |
| ---  | --- |
| addressCode | 城市代码 |
| cuserId | 用户ID |
| caccount | 公积金帐号 |
| businessType | 业务类型 |
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