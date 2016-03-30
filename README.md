##<A name="0">CMS-API</A>

API目录

|编号|接口|
|:------:|:-------|
|1|<A HREF="#1">检索名接口服务</A>|
|2|<A HREF="#2">其他</A>|

###<a name="1">1.检索名接口服务</a>

**1.1 接口**：
	
		com.viewstar.soa.nodejs.searchName.service.SearchNameService

**1.1.1 方法：获取检索名**

	getSearchNameInfo(vodName)；

**1.1.2 方法：输入参数**

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


**1.1.3 方法：输出参数**：

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

