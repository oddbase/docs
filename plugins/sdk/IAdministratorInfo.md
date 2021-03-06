# IAdministratorInfo interface

管理员实体接口。 对应数据库中的siteserver_Administrator表。

```csharp
public interface IAdministratorInfo
```

## Members

| name | description |
| --- | --- |
| [AreaId](sdk/IAdministratorInfo/AreaId.md) { get; set; } | 所在区域Id，对应 siteserver_Area 表的 Id 字段。 |
| [CountOfFailedLogin](sdk/IAdministratorInfo/CountOfFailedLogin.md) { get; set; } | 连续登录失败次数。 |
| [CountOfLogin](sdk/IAdministratorInfo/CountOfLogin.md) { get; set; } | 登录次数。 |
| [CreationDate](sdk/IAdministratorInfo/CreationDate.md) { get; set; } | 创建时间。 |
| [CreatorUserName](sdk/IAdministratorInfo/CreatorUserName.md) { get; set; } | 管理员创建者。 |
| [DepartmentId](sdk/IAdministratorInfo/DepartmentId.md) { get; set; } | 所属部门Id，对应 siteserver_Department 表的 Id 字段。 |
| [DisplayName](sdk/IAdministratorInfo/DisplayName.md) { get; set; } | 管理员显示名称。 |
| [Email](sdk/IAdministratorInfo/Email.md) { get; set; } | 电子邮箱，具有唯一性，可作为登录账号使用。 |
| [Id](sdk/IAdministratorInfo/Id.md) { get; set; } | 自增长主键。 |
| [IsLockedOut](sdk/IAdministratorInfo/IsLockedOut.md) { get; set; } | 是否被锁定。 |
| [LastActivityDate](sdk/IAdministratorInfo/LastActivityDate.md) { get; set; } | 最后活动时间。 |
| [Mobile](sdk/IAdministratorInfo/Mobile.md) { get; set; } | 手机号码，具有唯一性，可作为登录账号使用。 |
| [SiteId](sdk/IAdministratorInfo/SiteId.md) { get; set; } | 最后一次管理的站点Id。 |
| [SiteIdCollection](sdk/IAdministratorInfo/SiteIdCollection.md) { get; set; } | 拥有管理权限的站点Id列表。 |
| [UserName](sdk/IAdministratorInfo/UserName.md) { get; set; } | 管理员账号，具有唯一性。 |

## See Also

* namespace [SiteServer.Plugin](sdk/README.md)

<!-- DO NOT EDIT: generated by xmldocmd for SiteServer.Plugin.dll -->
