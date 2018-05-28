##获取帖子列表

#### @Author: WangYx @Date: 2018/5/28 

###接口路径：   
 * /community/articleList
 
###请求参数类型
| 字段 | 说明 |
| ---  | --- |
|cityTag|城市标签 |
|page|当前页|
|rows|一页记录数|
|tagName|标签名称直接传标签中文名|
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