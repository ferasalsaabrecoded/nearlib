---
id: "_generated_rpc_error_types_.guestpanic"
title: "GuestPanic"
sidebar_label: "GuestPanic"
---

## Hierarchy

  ↳ [HostError](_generated_rpc_error_types_.hosterror.md)

  ↳ **GuestPanic**

## Index

### Constructors

* [constructor](_generated_rpc_error_types_.guestpanic.md#constructor)

### Properties

* [index](_generated_rpc_error_types_.guestpanic.md#index)
* [message](_generated_rpc_error_types_.guestpanic.md#message)
* [name](_generated_rpc_error_types_.guestpanic.md#name)
* [panic_msg](_generated_rpc_error_types_.guestpanic.md#panic_msg)
* [stack](_generated_rpc_error_types_.guestpanic.md#optional-stack)
* [type](_generated_rpc_error_types_.guestpanic.md#type)

## Constructors

###  constructor

\+ **new GuestPanic**(`message?`: string, `type?`: string): *[GuestPanic](_generated_rpc_error_types_.guestpanic.md)*

*Inherited from [TypedError](_utils_errors_.typederror.md).[constructor](_utils_errors_.typederror.md#constructor)*

*Defined in [src.ts/utils/errors.ts:14](https://github.com/nearprotocol/nearlib/blob/36a8ddc/src.ts/utils/errors.ts#L14)*

**Parameters:**

Name | Type |
------ | ------ |
`message?` | string |
`type?` | string |

**Returns:** *[GuestPanic](_generated_rpc_error_types_.guestpanic.md)*

## Properties

###  index

• **index**: *any*

*Inherited from [ActionError](_generated_rpc_error_types_.actionerror.md).[index](_generated_rpc_error_types_.actionerror.md#index)*

*Defined in [src.ts/generated/rpc_error_types.ts:10](https://github.com/nearprotocol/nearlib/blob/36a8ddc/src.ts/generated/rpc_error_types.ts#L10)*

___

###  message

• **message**: *string*

*Inherited from void*

Defined in node_modules/typescript/lib/lib.es5.d.ts:974

___

###  name

• **name**: *string*

*Inherited from void*

Defined in node_modules/typescript/lib/lib.es5.d.ts:973

___

###  panic_msg

• **panic_msg**: *any*

*Defined in [src.ts/generated/rpc_error_types.ts:116](https://github.com/nearprotocol/nearlib/blob/36a8ddc/src.ts/generated/rpc_error_types.ts#L116)*

___

### `Optional` stack

• **stack**? : *string*

*Inherited from void*

*Overrides void*

Defined in node_modules/typescript/lib/lib.es5.d.ts:975

___

###  type

• **type**: *string*

*Inherited from [TypedError](_utils_errors_.typederror.md).[type](_utils_errors_.typederror.md#type)*

*Defined in [src.ts/utils/errors.ts:14](https://github.com/nearprotocol/nearlib/blob/36a8ddc/src.ts/utils/errors.ts#L14)*
