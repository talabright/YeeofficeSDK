# YeeofficeSDK
Summary：此SDK主要封装了内容列表的接口

调用示例


```
var context = AkmiiContext.GetAkmiiContext("对应环境的域名地址", "知普信息颁发的token");
var response = context.Repository.SelectByListIDAsync(new CustomDataGetListRequest
{
    AppID = 41,
    ListID = 1153194374738350080
}).Result;
```