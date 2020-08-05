---
lang: en
title: 'API docs: repository.defaultcrudrepository.execute_2'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.defaultcrudrepository.execute_2.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [DefaultCrudRepository](./repository.defaultcrudrepository.md) &gt; [execute](./repository.defaultcrudrepository.execute_2.md)

## DefaultCrudRepository.execute() method

Execute a raw database command using a connector that's not described by LoopBack's `execute` API yet.

\*\*WARNING:\*\* In general, it is always better to perform database actions through repository methods. Directly executing database commands may lead to unexpected results and other issues.

<b>Signature:</b>

```typescript
execute(...args: PositionalParameters): Promise<AnyObject>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  args | [PositionalParameters](./repository.positionalparameters.md) | Command and parameters, please consult your connector's documentation to learn about supported commands and their parameters. |

<b>Returns:</b>

Promise&lt;[AnyObject](./repository.anyobject.md)<!-- -->&gt;

A promise which resolves to the command output as returned by the database driver.

