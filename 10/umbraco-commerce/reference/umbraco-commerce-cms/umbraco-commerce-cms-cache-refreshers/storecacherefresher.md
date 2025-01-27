---
title: StoreCacheRefresher
description: API reference for StoreCacheRefresher in Umbraco Commerce
---
## StoreCacheRefresher

```csharp
public class StoreCacheRefresher : 
    UmbracoCommerceEntityStateCacheRefresherBase<StoreCacheRefresher, IStoreService, StoreReadOnly>
```

**Inheritance**

* class [UmbracoCommerceEntityStateCacheRefresherBase&lt;TInstanceType,TService,TEntity&gt;](umbracocommerceentitystatecacherefresherbase-3.md)

**Namespace**
* [Umbraco.Commerce.Cms.Cache.Refreshers](README.md)

### Constructors

#### StoreCacheRefresher

```csharp
public StoreCacheRefresher(AppCaches appCaches, IJsonSerializer serializer, 
    IEventAggregator eventAggregator, ICacheRefresherNotificationFactory factory, 
    Lazy<IStoreService> entityService, Lazy<ILogger<StoreCacheRefresher>> logger)
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
