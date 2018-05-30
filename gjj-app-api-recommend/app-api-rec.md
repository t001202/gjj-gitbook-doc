##推荐位接口
    
#### @Author: WangYx @Date: 2018/5/30 

###接口： 

| 接口 | 请求方式 | 接口方式 |
| ---  | --- | --- |
| /recommend/grouplist | GET | 获取推荐位 |
###推荐位包含：
    <code class=\"hljs javascript\">" +
        "获取推荐位,如首页快捷入口为一个推荐位，首页banner为一个推荐位：<br/>" +
        "locationKey取值如下 ：<br/>" +
        "service_banner_small ： 服务页banner广告位，2.9.1小图版<br/>" +
        "service_around_middle ： 服务页周边服务广告位，2.9.1双图版<br/>" +
        "service_entry_five ： 服务页快捷入口广告位，2.9.1伍个入口版<br/>" +
        "calculator_loan ： 计算器页面广告位，房贷计算机页面广告<br/>" +
        "calculator_house ： 计算器页面广告位，二手房计算机页面广告<br/>" +
        "<br/>推荐位接口说明：<br/>" +
        "以下为app接口/appapi/recommend接口的location_key参数说明。<br/>" +
        "V2.9.0-V3.0.0接口：<br/>" +
        "<br/>公积金首页推荐位接口location_key： <br/>"+
        "index_banner :首页banner</br>" +
        "index_banner_height  :首页bannerV2.9.1以上版本</br>" +
        "index_information:首页资讯</br>" +
        "index_entry:首页快捷入口</br>" +
        "index_calculator:金融工具</br>" +
        "index_loan:首页推荐贷款</br>" +
        "index_credit:首页公积金授信办卡</br>" +
        "index_credit_v290:首页公积金授信办卡V2.9.1以上版本</br>" +
        "index_credit_information :首页信用卡资讯</br>" +
        "<br/>公积金服务页推荐位location_key：</br>" +
        "service_banner ::服务页banner </br>" +
        "service_banner_small:服务页bannerV2.9.1以上版本</br>" +
        "service_entry :服务页快捷入口</br>" +
        "service_entry_five:服务页快捷入口V2.9.1以上版本</br>" +
        "service_around :服务页周边服务</br>" +
        "service_around_middle:服务页周边服务V2.9.1以上版本</br>" +
        "service_adv:服务页面广告(更多服务->缴存指南)</br>" +
        "service_loan:急需用钱?轻松速贷(更多服务->缴存指南):</br>" +
        "<br/>公积金详情页推荐位location_key：</br>" +
        "detail_banner:详情页banner</br>" +
        "detail_gjjloan:详情页授信贷(单独接口:/appapi/recommend/detail/gjjloan)</br>" +
        "<br/>公积金启动全屏推荐位location_key：</br>" +
        "start_screen:启动全屏广告(单独接口:/appapi/recommend/start/screen)</br>" +
        "<br/>公积金弹框推荐位location_key：</br>" +
        "alert_start:弹框广告</br>" +
        "<br/>公积金计算机页面推荐位location_key：</br>" +
        "calculator_loan:计算器房贷页面广告</br>" +
        "calculator_house:计算器二手房页面广告</br>" +
        "V3.0.1接口：</br>" +
        "<br/>公积金信用卡页面推荐位location_key：</br>" +
        "gjj_credit_hot_list:  :本月最热卡榜</br>" +
        "gjj_credit_hot_bank:  :热门银行</br>" +
        "gjj_credit_fast_entry:快捷入口</br>" +
        "gjj_credit_select_entry: 精选办卡入口</br>" +
        "gjj_credit_hot_comment :上榜好评</br>" +
        "<br/>社保首页推荐位location_key：</br>" +
        "si_index_banner:社保首页</br>" +
        "si_index_entry:社保首页快捷入口</br>" +
        "si_index_select_loan:社保首页精选贷款</br>" +
        "si_index_select_loan_information:社保首页精选贷款资讯</br>" +
        "si_index_loan_list:社保首页今日产品榜</br>" +
        "</br>" +
        "</code>

###请求参数类型：
| 字段 | 说明 |
| ---  | --- |
| locationKey | 推荐位key |
| mobileType | 客户端类型 1:安卓 2:iOS 3:其他 |
| source | 渠道source值 |
| existenceType | 数据类型：1：正式数据 0：审核数据，默认值：1 |

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