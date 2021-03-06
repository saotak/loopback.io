---
lang: en
title: 'API docs: context.createviewgetter_1'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.context.createviewgetter_1.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [createViewGetter](./context.createviewgetter_1.md)

## createViewGetter() function

Create a context view as a getter with the given filter and sort matched bindings by the comparator.

<b>Signature:</b>

```typescript
export declare function createViewGetter<T = unknown>(ctx: Context, bindingFilter: BindingFilter, bindingComparator?: BindingComparator, session?: ResolutionSession): Getter<T[]>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  ctx | <code>Context</code> | Context object |
|  bindingFilter | <code>BindingFilter</code> | A function to match bindings |
|  bindingComparator | <code>BindingComparator</code> | A function to compare two bindings |
|  session | <code>ResolutionSession</code> | Resolution session |

<b>Returns:</b>

`Getter<T[]>`


