# YeeofficeSDK
Summary����SDK��Ҫ��װ�������б�Ľӿ�

����ʾ��


```
var context = AkmiiContext.GetAkmiiContext("��Ӧ������������ַ", "֪����Ϣ�䷢��token");
var response = context.Repository.SelectByListIDAsync(new CustomDataGetListRequest
{
    AppID = 41,
    ListID = 1153194374738350080
}).Result;
```