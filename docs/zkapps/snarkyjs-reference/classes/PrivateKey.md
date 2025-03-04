# Class: PrivateKey

A signing key. You can generate one via [random](PrivateKey.md#random).

## Hierarchy

- [`CircuitValue`](CircuitValue.md)

  ↳ **`PrivateKey`**

## Table of contents

### Constructors

- [constructor](PrivateKey.md#constructor)

### Properties

- [s](PrivateKey.md#s)

### Methods

- [assertEquals](PrivateKey.md#assertequals)
- [equals](PrivateKey.md#equals)
- [isConstant](PrivateKey.md#isconstant)
- [toBase58](PrivateKey.md#tobase58)
- [toConstant](PrivateKey.md#toconstant)
- [toFields](PrivateKey.md#tofields)
- [toJSON](PrivateKey.md#tojson)
- [toPublicKey](PrivateKey.md#topublickey)
- [check](PrivateKey.md#check)
- [fromBase58](PrivateKey.md#frombase58)
- [fromBits](PrivateKey.md#frombits)
- [fromFields](PrivateKey.md#fromfields)
- [fromJSON](PrivateKey.md#fromjson)
- [fromObject](PrivateKey.md#fromobject)
- [random](PrivateKey.md#random)
- [sizeInFields](PrivateKey.md#sizeinfields)
- [toAuxiliary](PrivateKey.md#toauxiliary)
- [toBase58](PrivateKey.md#tobase58-1)
- [toConstant](PrivateKey.md#toconstant-1)
- [toFields](PrivateKey.md#tofields-1)
- [toInput](PrivateKey.md#toinput)
- [toJSON](PrivateKey.md#tojson-1)

## Constructors

### constructor

• **new PrivateKey**(...`props`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `...props` | `any`[] |

#### Inherited from

[CircuitValue](CircuitValue.md).[constructor](CircuitValue.md#constructor)

#### Defined in

[lib/circuit_value.ts:65](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L65)

## Properties

### s

• **s**: [`Scalar`](Scalar.md)

#### Defined in

[lib/signature.ts:12](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/signature.ts#L12)

## Methods

### assertEquals

▸ **assertEquals**(`x`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`PrivateKey`](PrivateKey.md) |

#### Returns

`void`

#### Inherited from

[CircuitValue](CircuitValue.md).[assertEquals](CircuitValue.md#assertequals)

#### Defined in

[lib/circuit_value.ts:153](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L153)

___

### equals

▸ **equals**(`x`): [`Bool`](Bool.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`PrivateKey`](PrivateKey.md) |

#### Returns

[`Bool`](Bool.md)

#### Inherited from

[CircuitValue](CircuitValue.md).[equals](CircuitValue.md#equals)

#### Defined in

[lib/circuit_value.ts:149](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L149)

___

### isConstant

▸ **isConstant**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CircuitValue](CircuitValue.md).[isConstant](CircuitValue.md#isconstant)

#### Defined in

[lib/circuit_value.ts:157](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L157)

___

### toBase58

▸ **toBase58**(): `string`

#### Returns

`string`

#### Defined in

[lib/signature.ts:48](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/signature.ts#L48)

___

### toConstant

▸ **toConstant**(): [`PrivateKey`](PrivateKey.md)

#### Returns

[`PrivateKey`](PrivateKey.md)

#### Inherited from

[CircuitValue](CircuitValue.md).[toConstant](CircuitValue.md#toconstant)

#### Defined in

[lib/circuit_value.ts:145](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L145)

___

### toFields

▸ **toFields**(): [`Field`](Field.md)[]

#### Returns

[`Field`](Field.md)[]

#### Inherited from

[CircuitValue](CircuitValue.md).[toFields](CircuitValue.md#tofields)

#### Defined in

[lib/circuit_value.ts:137](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L137)

___

### toJSON

▸ **toJSON**(): `any`

#### Returns

`any`

#### Inherited from

[CircuitValue](CircuitValue.md).[toJSON](CircuitValue.md#tojson)

#### Defined in

[lib/circuit_value.ts:141](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L141)

___

### toPublicKey

▸ **toPublicKey**(): [`PublicKey`](Types.PublicKey.md)

Derives the associated public key.

#### Returns

[`PublicKey`](Types.PublicKey.md)

a [PublicKey](../README.md#publickey).

#### Defined in

[lib/signature.ts:40](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/signature.ts#L40)

___

### check

▸ `Static` **check**<`T`\>(`this`, `v`): `void`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `v` | `InstanceType`<`T`\> |

#### Returns

`void`

#### Inherited from

[CircuitValue](CircuitValue.md).[check](CircuitValue.md#check)

#### Defined in

[lib/circuit_value.ts:186](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L186)

___

### fromBase58

▸ `Static` **fromBase58**(`privateKeyBase58`): [`PrivateKey`](PrivateKey.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `privateKeyBase58` | `string` |

#### Returns

[`PrivateKey`](PrivateKey.md)

#### Defined in

[lib/signature.ts:44](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/signature.ts#L44)

___

### fromBits

▸ `Static` **fromBits**(`bs`): [`PrivateKey`](PrivateKey.md)

Deserializes a list of bits into a [PrivateKey](PrivateKey.md).

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `bs` | [`Bool`](Bool.md)[] | a list of [Bool](Bool.md)s. |

#### Returns

[`PrivateKey`](PrivateKey.md)

a [PrivateKey](PrivateKey.md).

#### Defined in

[lib/signature.ts:31](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/signature.ts#L31)

___

### fromFields

▸ `Static` **fromFields**<`T`\>(`this`, `xs`): `InstanceType`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `xs` | [`Field`](Field.md)[] |

#### Returns

`InstanceType`<`T`\>

#### Inherited from

[CircuitValue](CircuitValue.md).[fromFields](CircuitValue.md#fromfields)

#### Defined in

[lib/circuit_value.ts:161](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L161)

___

### fromJSON

▸ `Static` **fromJSON**<`T`\>(`this`, `value`): ``null`` \| `InstanceType`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `value` | `any` |

#### Returns

``null`` \| `InstanceType`<`T`\>

#### Inherited from

[CircuitValue](CircuitValue.md).[fromJSON](CircuitValue.md#fromjson)

#### Defined in

[lib/circuit_value.ts:219](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L219)

___

### fromObject

▸ `Static` **fromObject**<`T`\>(`this`, `value`): `InstanceType`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `value` | `NonMethods`<`InstanceType`<`T`\>\> |

#### Returns

`InstanceType`<`T`\>

#### Inherited from

[CircuitValue](CircuitValue.md).[fromObject](CircuitValue.md#fromobject)

#### Defined in

[lib/circuit_value.ts:82](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L82)

___

### random

▸ `Static` **random**(): [`PrivateKey`](PrivateKey.md)

You can use this method to generate a private key. You can then obtain
the associated public key via [toPublicKey](PrivateKey.md#topublickey). And generate signatures
via [Signature.create](Signature.md#create).

#### Returns

[`PrivateKey`](PrivateKey.md)

a new [PrivateKey](PrivateKey.md).

#### Defined in

[lib/signature.ts:21](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/signature.ts#L21)

___

### sizeInFields

▸ `Static` **sizeInFields**(): `number`

#### Returns

`number`

#### Inherited from

[CircuitValue](CircuitValue.md).[sizeInFields](CircuitValue.md#sizeinfields)

#### Defined in

[lib/circuit_value.ts:89](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L89)

___

### toAuxiliary

▸ `Static` **toAuxiliary**(): []

#### Returns

[]

#### Inherited from

[CircuitValue](CircuitValue.md).[toAuxiliary](CircuitValue.md#toauxiliary)

#### Defined in

[lib/circuit_value.ts:111](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L111)

___

### toBase58

▸ `Static` **toBase58**(`privateKey`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `privateKey` | `Object` |
| `privateKey.s` | [`Scalar`](Scalar.md) |

#### Returns

`string`

#### Defined in

[lib/signature.ts:52](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/signature.ts#L52)

___

### toConstant

▸ `Static` **toConstant**<`T`\>(`this`, `t`): `InstanceType`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `t` | `InstanceType`<`T`\> |

#### Returns

`InstanceType`<`T`\>

#### Inherited from

[CircuitValue](CircuitValue.md).[toConstant](CircuitValue.md#toconstant-1)

#### Defined in

[lib/circuit_value.ts:200](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L200)

___

### toFields

▸ `Static` **toFields**<`T`\>(`this`, `v`): [`Field`](Field.md)[]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `v` | `InstanceType`<`T`\> |

#### Returns

[`Field`](Field.md)[]

#### Inherited from

[CircuitValue](CircuitValue.md).[toFields](CircuitValue.md#tofields-1)

#### Defined in

[lib/circuit_value.ts:94](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L94)

___

### toInput

▸ `Static` **toInput**<`T`\>(`this`, `v`): `HashInput`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `v` | `InstanceType`<`T`\> |

#### Returns

`HashInput`

#### Inherited from

[CircuitValue](CircuitValue.md).[toInput](CircuitValue.md#toinput)

#### Defined in

[lib/circuit_value.ts:115](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L115)

___

### toJSON

▸ `Static` **toJSON**<`T`\>(`this`, `v`): `any`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `v` | `InstanceType`<`T`\> |

#### Returns

`any`

#### Inherited from

[CircuitValue](CircuitValue.md).[toJSON](CircuitValue.md#tojson-1)

#### Defined in

[lib/circuit_value.ts:208](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/circuit_value.ts#L208)
