---
title: OrderOrderNumberAdvancedFilter
description: API reference for OrderOrderNumberAdvancedFilter in Umbraco Commerce
---
## OrderOrderNumberAdvancedFilter

```csharp
public class OrderOrderNumberAdvancedFilter : OrderAdvancedFilterBase
```

**Inheritance**

* class [OrderAdvancedFilterBase](../umbraco-commerce-cms-filters/orderadvancedfilterbase.md)

**Namespace**
* [Umbraco.Commerce.Cms.Filters.Implement](README.md)

### Constructors

#### OrderOrderNumberAdvancedFilter

The default constructor.

```csharp
public OrderOrderNumberAdvancedFilter()
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
