---
title: RegionCacheRefresher
description: API reference for RegionCacheRefresher in Umbraco Commerce
---
## RegionCacheRefresher

```csharp
public class RegionCacheRefresher : 
    UmbracoCommerceEntityStateCacheRefresherBase<RegionCacheRefresher, ICountryService, RegionReadOnly>
```

**Inheritance**

* class [UmbracoCommerceEntityStateCacheRefresherBase&lt;TInstanceType,TService,TEntity&gt;](umbracocommerceentitystatecacherefresherbase-3.md)

**Namespace**
* [Umbraco.Commerce.Cms.Cache.Refreshers](README.md)

### Constructors

#### RegionCacheRefresher

```csharp
public RegionCacheRefresher(AppCaches appCaches, IJsonSerializer serializer, 
    IEventAggregator eventAggregator, ICacheRefresherNotificationFactory factory, 
    Lazy<ICountryService> entityService, Lazy<ILogger<RegionCacheRefresher>> logger)
```


### Properties

#### Name

```csharp
public override string Name { get; }
```


---

#### RefresherUniqueId

```csharp
public override Guid RefresherUniqueId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.dll -->
