# IChannelApi.GetChannelName method

通过站点Id以及栏目Id获取栏目名称。

```csharp
public string GetChannelName(int siteId, int channelId)
```

| parameter | description |
| --- | --- |
| siteId | 站点Id。 |
| channelId | 栏目Id。 |

## Return Value

如果对应的栏目存在，则返回栏目名称；否则返回 null。

## See Also

* interface [IChannelApi](sdk/IChannelApi.md)
* namespace [SiteServer.Plugin](sdk/README.md)

<!-- DO NOT EDIT: generated by xmldocmd for SiteServer.Plugin.dll -->
