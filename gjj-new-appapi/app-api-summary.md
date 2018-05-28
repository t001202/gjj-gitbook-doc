#公积金推荐位
    /**
     * @Author: WangYx
     * @Date: 11:20 2018/5/28 
     * @Params: 
     * @Description:
     * 公积金后台接口文档说明
     */
###有鱼金融公积金APP接口，适用于V2.9.0版本及以上版本
    1.接口地址：http://ip:port/appapi,eg. 开发环境:http://devgjjapi.gs.youyuwo.com/appapi 
    2.需登陆的接口请先使用『登陆调试接口』登陆后再调用
    3.APP调用接口时，标注『需登录』的接口需要额外请求参数（支持header传参，表单传参，cookie，推荐使用header传参）：
        参数说明：
        - appId: 登录后获取的appId , 必需参数
        - accessToken:登录后获取的accessToken , 必需参数
        - source: 渠道值 , 必需参数
        - mobileType: 客户端类型 1:安卓 2:iOS 3:其他 , 必需参数
        - packageType: 包类型 9:公积金 4:社保 10:贷款 , 必需参数 ,默认值：9， V3.1.0（含）以上版本需要此参数，
        - loginFrom: 登陆来源 HSK:惠刷卡 GJJ:公积金 JZ:记账,默认:GJJ , 非必需参数
        - packageName:包名 , 非必需参数
        - version: 版本号 , 必需参数 ,兼容原releaseVersion参数
    4.http响应码说明：
        - 200 : 成功响应
        - 404 : 接口不存在
    5.code码说明： 
        - -1 : 未登录（遵循用户中心响应码规则）
        - 1 : 操作成功
        - 461 : 参数错误
        - 500 : 开发环境-> 返回异常信息，用于调试，快速定位问题；测试环境&正式环境 -> 返回“系统异常”
        - 其他请参照各个接口描述，各个接口均有不同