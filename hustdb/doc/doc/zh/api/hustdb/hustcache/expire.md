## expire ##

**接口:** `/hustcache/expire`

**方法:** `GET`

**参数:** 

*  **key** （必选）    
*  **ttl** （必选）

**使用范例A:**

    curl -i -X GET "http://localhost:8085/hustcache/expire?key=test_key&ttl=60"

**结果范例A1:**

	HTTP/1.1 404 Not Found
		
**结果范例A2:**

	HTTP/1.1 200 OK
	
[上一级](../hustcache.md)

[根目录](../../../index.md)