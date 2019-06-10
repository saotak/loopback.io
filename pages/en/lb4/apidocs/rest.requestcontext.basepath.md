---
lang: en
title: 'API docs: rest.requestcontext.basepath'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.rest.requestcontext.basepath.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/rest](./rest.md) &gt; [RequestContext](./rest.requestcontext.md) &gt; [basePath](./rest.requestcontext.basepath.md)

## RequestContext.basePath property

Get the effective base path of the incoming request. This base path combines `baseUrl` provided by Express when LB4 handler is mounted on a non-root path, with the `basePath` value configured at LB4 side.

<b>Signature:</b>

```typescript
readonly basePath: string;
```
