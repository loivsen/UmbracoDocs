---
title: OrderLastUpdatedAfterAdvancedFilter
description: API reference for OrderLastUpdatedAfterAdvancedFilter in Umbraco Commerce
---
## OrderLastUpdatedAfterAdvancedFilter

```csharp
public class OrderLastUpdatedAfterAdvancedFilter : OrderAdvancedFilterBase
```

**Inheritance**

* class [OrderAdvancedFilterBase](../umbraco-commerce-cms-filters/orderadvancedfilterbase.md)

**Namespace**
* [Umbraco.Commerce.Cms.Filters.Implement](README.md)

### Constructors

#### OrderLastUpdatedAfterAdvancedFilter

The default constructor.

```csharp
public OrderLastUpdatedAfterAdvancedFilter()
```


### Methods

#### Apply

```csharp
public override IQuerySpecification<OrderReadOnly> Apply(IQuerySpecification<OrderReadOnly> query, 
    IOrderQuerySpecificationFactory where, string value)
```


---

#### CanApply

```csharp
public override bool CanApply(string value)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.dll -->
