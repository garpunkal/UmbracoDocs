---
title: OrderLastUpdatedBeforeAdvancedFilter
description: API reference for OrderLastUpdatedBeforeAdvancedFilter in Umbraco Commerce
---
## OrderLastUpdatedBeforeAdvancedFilter

```csharp
public class OrderLastUpdatedBeforeAdvancedFilter : OrderAdvancedFilterBase
```

**Inheritance**

* class [OrderAdvancedFilterBase](../umbraco-commerce-cms-filters/orderadvancedfilterbase.md)

**Namespace**
* [Umbraco.Commerce.Cms.Filters.Implement](README.md)

### Constructors

#### OrderLastUpdatedBeforeAdvancedFilter

The default constructor.

```csharp
public OrderLastUpdatedBeforeAdvancedFilter()
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
