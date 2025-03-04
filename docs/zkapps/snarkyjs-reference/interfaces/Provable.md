# Interface: Provable<T\>

`Provable<T>` is the general circuit type interface. It describes how a type `T` is made up of field elements and auxiliary (non-field element) data.

You will find this as the required input type in a few places in snarkyjs. One convenient way to create a `Provable<T>` is using `Struct`.

## Type parameters

| Name |
| :------ |
| `T` |

## Hierarchy

- **`Provable`**

  ↳ [`ProvablePure`](ProvablePure.md)

## Table of contents

### Properties

- [check](Provable.md#check)
- [fromFields](Provable.md#fromfields)
- [toAuxiliary](Provable.md#toauxiliary)
- [toFields](Provable.md#tofields)

### Methods

- [sizeInFields](Provable.md#sizeinfields)

## Properties

### check

• **check**: (`x`: `T`) => `void`

#### Type declaration

▸ (`x`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `T` |

##### Returns

`void`

#### Defined in

[snarky.d.ts:29](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/snarky.d.ts#L29)

___

### fromFields

• **fromFields**: (`x`: [`Field`](../classes/Field.md)[], `aux`: `any`[]) => `T`

#### Type declaration

▸ (`x`, `aux`): `T`

##### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`Field`](../classes/Field.md)[] |
| `aux` | `any`[] |

##### Returns

`T`

#### Defined in

[snarky.d.ts:27](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/snarky.d.ts#L27)

___

### toAuxiliary

• **toAuxiliary**: (`x?`: `T`) => `any`[]

#### Type declaration

▸ (`x?`): `any`[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `x?` | `T` |

##### Returns

`any`[]

#### Defined in

[snarky.d.ts:26](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/snarky.d.ts#L26)

___

### toFields

• **toFields**: (`x`: `T`) => [`Field`](../classes/Field.md)[]

#### Type declaration

▸ (`x`): [`Field`](../classes/Field.md)[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `T` |

##### Returns

[`Field`](../classes/Field.md)[]

#### Defined in

[snarky.d.ts:25](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/snarky.d.ts#L25)

## Methods

### sizeInFields

▸ **sizeInFields**(): `number`

#### Returns

`number`

#### Defined in

[snarky.d.ts:28](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/snarky.d.ts#L28)
