---
title: PipelineTaskCollection<T,TResult>
description: API reference for PipelineTaskCollection<T,TResult> in Umbraco Commerce
---
## PipelineTaskCollection&lt;T,TResult&gt;

```csharp
public class PipelineTaskCollection<T, TResult> : ComposedCollection<IPipelineTask<T, TResult>>, 
    IComposedCollection<IPipelineTask<T, TResult>>, IComposedCollection<IPipelineTask>, 
    IEnumerable<IPipelineTask<T, TResult>>, IEnumerable<IPipelineTask>, 
    IPipelineTaskCollection<T, TResult>, IReadOnlyCollection<IPipelineTask<T, TResult>>, 
    IReadOnlyCollection<IPipelineTask>
```

**Inheritance**

* class [ComposedCollection&lt;T&gt;](../umbraco-commerce-common-composing/composedcollection-1.md)
* interface [IComposedCollection&lt;T&gt;](../umbraco-commerce-common-composing/icomposedcollection-1.md)
* interface [IPipelineTaskCollection&lt;T,TResult&gt;](ipipelinetaskcollection-2.md)

**Namespace**
* [Umbraco.Commerce.Common.Pipelines](README.md)

### Constructors

#### PipelineTaskCollection&lt;T,TResult&gt;

```csharp
public PipelineTaskCollection(Func<IEnumerable<IPipelineTask<T, TResult>>> itemsFactory)
```


### Properties

#### OnFail

```csharp
public IPipelineAction<T> OnFail { get; set; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Common.dll -->
