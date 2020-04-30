<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [@bytesoftio/use-async](#bytesoftiouse-async)
  - [Installation](#installation)
  - [Description](#description)
  - [Usage](#usage)
    - [createTimeout](#createtimeout)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# @bytesoftio/use-async

## Installation

`yarn add @bytesoftio/helpers-promises` or `npm install @bytesoftio/helpers
-promises`

## Description

A collection of promises related helpers.

## Usage

### createTimeout

A promisified verion of the `setTimeout` function.

```ts
import { createTimeout } from "@bytesoftio/helpers-promises"

await createTimeout(2000)
```