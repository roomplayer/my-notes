##### BrowserContext.实例属性
- `BrowserContext.background_pages` -> List[Page]
	- 返回浏览器上下文的后台页面列表
- `BrowserContext.browser` -> NoneType|Browser
	- 返回与浏览器上下文关联的浏览器实例，如果没有关联则返回 None
- `BrowserContext.pages` -> List[Page]
	- 返回浏览器上下文中的所有页面列表
- `BrowserContext.request` -> [[class APIRequestContext|APIRequestContext]]
	- 返回浏览器上下文的 API 请求上下文对象
- `BrowserContext.service_workers` -> List[Worker]
	- 返回浏览器上下文中的所有 Service Worker 列表
- `BrowserContext.tracing` -> [[class Tracing|Tracing]]
	- 返回浏览器上下文的跟踪对象
