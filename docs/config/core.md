---
id: core
title: Core Config
---

## `core.secure`
Whether or not to use https or not

**Type**: `boolean`
**Env Property**: `SECURE`
**Example:**:
```js
true
```

## `core.secret`
Whether or not to use https or not

**Type**: `string`
**Env Property**: `SECRET`
**Example:**:
```js
'1234567890qwertyuiopasdfghjklzxcvbnm'
```

## `core.host`
What host Zipline should run on.
:::info
If using Docker, set the value to `'0.0.0.0'`
:::

**Type**: `string`
**Env Property**: `HOST`
**Example:**:
```js
'0.0.0.0'
```

## `core.port`
What port Zipline should run on

**Type**: `number`
**Env Property**: `PORT`
**Example:**:
```js
3000
```
