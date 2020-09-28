# @bytesoftio/helpers-promises

## Installation

`yarn add @bytesoftio/helpers-promises` or `npm install @bytesoftio/helpers-promises`

## Table of contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Description](#description)
- [createTimeout](#createtimeout)
- [createPromise](#createpromise)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

A collection of promises related helpers.

## createTimeout

A promisified verion of the `setTimeout` function.

```ts
import { createTimeout } from "@bytesoftio/helpers-promises"

await createTimeout(2000)
```

## createPromise

Create a promise that you can pass around without specifying the resolve function first.

```ts
import { createPromise } from "@bytesoftio/helpers-promises"

const promise = createPromise()

// pass promise to another function
runWhenResolved(promise)

promise.resolve("your data")
// or
promise.reject("reason...")
```
