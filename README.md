##<A name="0">CMS-API</A>

##### <A HREF="#1">1.检索名接口服务</A>
##### <A HREF="#2">2.其他</A>

###<a name="1">1.检索名接口服务</a>

**1.1 接口**：
	
		com.viewstar.soa.nodejs.searchName.service.SearchNameService

**1.2 输入参数**：

	(1) 名称
		
		类型：String
		
		长度：10
	
		默认值：无

		参数描述：待生成检索名的名称。

	(2) 整型参数
	
		类型：int

		默认值：无

		参数描述：

	(3) 布尔型参数
	
		类型：boolean
	
		默认值：无

		参数描述：


**1.3 输出参数**：

	例如：
		类型：Map<String,Object>

		参数描述:返回状态及结果
				|描述|key|value|
				|:------:|:-------:|:-------:|
				|状态|status|0或1|
				|结果|result|success或failed|

	例如：
		类型：List<String>

		参数描述：返回id编号集合 
				[123,456,789]

	例如：
		类型：vodInfo

		描述：返回vod实体信息
			vodInfo{
			  		id:"123",
			  		name:"vod"
					}

###<a name="2">2.其他</a><A HREF="#0">(顶)</A>
|         序号    |    交易名    |    交易说明    |    备注    |
|    ------: |    :-------:    |    :---------   |    ------    |
|    1    |    prfcfg    |    菜单配置    |    可以通过此交易查询到所有交易码和菜单的对应关系    |
|    2    |    gentmo    |    编译所有交易    |    |
|    100000    |    sysdba    |    数据库表模型汇总    |    |

