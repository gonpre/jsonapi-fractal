[jsonapi-fractal](../README.md) / JsonApiFractalError

# Class: JsonApiFractalError

## Hierarchy

- `Error`

  ↳ **`JsonApiFractalError`**

## Table of contents

### Constructors

- [constructor](JsonApiFractalError.md#constructor)

### Properties

- [message](JsonApiFractalError.md#message)
- [name](JsonApiFractalError.md#name)
- [stack](JsonApiFractalError.md#stack)
- [prepareStackTrace](JsonApiFractalError.md#preparestacktrace)
- [stackTraceLimit](JsonApiFractalError.md#stacktracelimit)

### Methods

- [captureStackTrace](JsonApiFractalError.md#capturestacktrace)

## Constructors

### constructor

• **new JsonApiFractalError**(`message`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |

#### Overrides

Error.constructor

#### Defined in

[src/errors.ts:2](https://github.com/andersondanilo/jsonapi-fractal/blob/fc0b05d/src/errors.ts#L2)

## Properties

### message

• **message**: `string`

#### Inherited from

Error.message

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1041

___

### name

• **name**: `string`

#### Inherited from

Error.name

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1040

___

### stack

• `Optional` **stack**: `string`

#### Inherited from

Error.stack

#### Defined in

node_modules/typescript/lib/lib.es5.d.ts:1042

___

### prepareStackTrace

▪ `Static` `Optional` **prepareStackTrace**: (`err`: `Error`, `stackTraces`: `CallSite`[]) => `any`

#### Type declaration

▸ (`err`, `stackTraces`): `any`

Optional override for formatting stack traces

**`See`**

https://v8.dev/docs/stack-trace-api#customizing-stack-traces

##### Parameters

| Name | Type |
| :------ | :------ |
| `err` | `Error` |
| `stackTraces` | `CallSite`[] |

##### Returns

`any`

#### Inherited from

Error.prepareStackTrace

#### Defined in

node_modules/@types/node/globals.d.ts:11

___

### stackTraceLimit

▪ `Static` **stackTraceLimit**: `number`

#### Inherited from

Error.stackTraceLimit

#### Defined in

node_modules/@types/node/globals.d.ts:13

## Methods

### captureStackTrace

▸ `Static` **captureStackTrace**(`targetObject`, `constructorOpt?`): `void`

Create .stack property on a target object

#### Parameters

| Name | Type |
| :------ | :------ |
| `targetObject` | `object` |
| `constructorOpt?` | `Function` |

#### Returns

`void`

#### Inherited from

Error.captureStackTrace

#### Defined in

node_modules/@types/node/globals.d.ts:4
