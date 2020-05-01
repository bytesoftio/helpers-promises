# @bytesoftio/use-async

## Installation

`yarn add @bytesoftio/helpers-promises` or `npm install @bytesoftio/helpers-promises`

## Table of contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Description](#description)
- [createTimeout](#createtimeout)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

A collection of promises related helpers.

## createTimeout

A promisified verion of the `setTimeout` function.

```ts
import { createTimeout } from "@bytesoftio/helpers-promises"

await createTimeout(2000)
```