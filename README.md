##<A name="0">CMS-API</A>

API目录

|编号|接口|方法|
|:------:|:-------|:-------|
|1|<A HREF="#1">检索名接口服务</A>|<A HREF="#1.1">获取检索名1</A>，<A HREF="#1.2">获取检索名2</A>，<A HREF="#1.2">获取检索名2</A>，<A HREF="#1.2">获取检索名2</A>，<br><A HREF="#1.2">获        取检索名2</A>，<A HREF="#1.2">获取检索名2</A>，<A HREF="#1.2">获取检索名2</A>，<A HREF="#1.2">获取检索名2<A>|
|2|<A HREF="#2">其他</A>||

###<a name="1">1.检索名接口服务</a>

		package：com.viewstar.soa.nodejs.searchName.service.SearchNameService

**1.1.1 方法：<a name="1.1">获取检索名1</a>**

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
					{"status":"0","result":"success"}
				或  
					{"status":?,"result":?}

		例如：
			类型：List<String>

			参数描述：返回id编号集合 
					[123,456,789,....]

		例如：
			类型：vodInfo

			描述：返回vod实体信息
				vodInfo:{id:"123",name:"vod"....}

**1.2 方法：<a name="1.2">获取检索名2</a>**

		getSearchNameInfo(vodName)；

**1.2.2 方法：输入参数**

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
					{"status":"0","result":"success"}
				或  
					{"status":?,"result":?}

		例如：
			类型：List<String>

			参数描述：返回id编号集合 
					[123,456,789,....]

		例如：
			类型：vodInfo

			描述：返回vod实体信息
				vodInfo:{id:"123",name:"vod"....}
###<a name="2">2.其他</a><A HREF="#0">(顶)</A>

