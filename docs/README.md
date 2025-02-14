tontools

# tontools

## Table of contents

### Type aliases

- [AddressType](README.md#addresstype)
- [Bit](README.md#bit)

### Classes

- [Address](classes/Address.md)
- [BitArray](classes/BitArray.md)
- [Cell](classes/Cell.md)
- [BoC](classes/BoC.md)
- [Slice](classes/Slice.md)
- [Coins](classes/Coins.md)
- [MsgTemplate](classes/MsgTemplate.md)
- [KeyPair](classes/KeyPair.md)

### Interfaces

- [SerializationOptions](interfaces/SerializationOptions.md)

### Functions

- [deserializeFift](README.md#deserializefift)
- [deserialize](README.md#deserialize)
- [serialize](README.md#serialize)
- [crc16BytesBe](README.md#crc16bytesbe)
- [crc32cBytesLe](README.md#crc32cbytesle)
- [uint8toInt8](README.md#uint8toint8)
- [int8ToUint8](README.md#int8touint8)
- [uintToHex](README.md#uinttohex)
- [hexToBits](README.md#hextobits)
- [hexToBytes](README.md#hextobytes)
- [bitsToHex](README.md#bitstohex)
- [bitsToBytes](README.md#bitstobytes)
- [bytesToUint](README.md#bytestouint)
- [bytesCompare](README.md#bytescompare)
- [bytesToBits](README.md#bytestobits)
- [bytesToHex](README.md#bytestohex)
- [bytesToString](README.md#bytestostring)
- [stringToBytes](README.md#stringtobytes)
- [bytesToBase64](README.md#bytestobase64)
- [base64ToBytes](README.md#base64tobytes)
- [sliceIntoChunks](README.md#sliceintochunks)

### Properties

- [bip0039en](README.md#bip0039en)

## Type aliases

### AddressType

Ƭ **AddressType**: ``"base64"`` \| ``"raw"``

___

### Bit

Ƭ **Bit**: ``0`` \| ``1``

## Functions

### deserializeFift

▸ **deserializeFift**(`data`): [`Cell`](classes/Cell.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `string` |

#### Returns

[`Cell`](classes/Cell.md)[]

___

### deserialize

▸ **deserialize**(`data`): [`Cell`](classes/Cell.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Uint8Array` |

#### Returns

[`Cell`](classes/Cell.md)[]

___

### serialize

▸ **serialize**(`root`, `options?`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `root` | [`Cell`](classes/Cell.md) |
| `options` | [`SerializationOptions`](interfaces/SerializationOptions.md) |

#### Returns

`Uint8Array`

___

### crc16BytesBe

▸ **crc16BytesBe**(`data`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Uint8Array` \| `number`[] |

#### Returns

`Uint8Array`

___

### crc32cBytesLe

▸ **crc32cBytesLe**(`data`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Uint8Array` \| `number`[] |

#### Returns

`Uint8Array`

___

### uint8toInt8

▸ **uint8toInt8**(`uint8`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `uint8` | `number` |

#### Returns

`number`

___

### int8ToUint8

▸ **int8ToUint8**(`int8`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `int8` | `number` |

#### Returns

`number`

___

### uintToHex

▸ **uintToHex**(`uint`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `uint` | `number` |

#### Returns

`string`

___

### hexToBits

▸ **hexToBits**(`hex`): [`Bit`](README.md#bit)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `hex` | `string` |

#### Returns

[`Bit`](README.md#bit)[]

___

### hexToBytes

▸ **hexToBytes**(`hex`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `hex` | `string` |

#### Returns

`Uint8Array`

___

### bitsToHex

▸ **bitsToHex**(`bits`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bits` | [`Bit`](README.md#bit)[] |

#### Returns

`string`

___

### bitsToBytes

▸ **bitsToBytes**(`bits`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bits` | [`Bit`](README.md#bit)[] |

#### Returns

`Uint8Array`

___

### bytesToUint

▸ **bytesToUint**(`bytes`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bytes` | `Uint8Array` \| `number`[] |

#### Returns

`number`

___

### bytesCompare

▸ **bytesCompare**(`a`, `b`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `Uint8Array` \| `number`[] |
| `b` | `Uint8Array` \| `number`[] |

#### Returns

`boolean`

___

### bytesToBits

▸ **bytesToBits**(`data`): [`Bit`](README.md#bit)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Uint8Array` \| `number`[] |

#### Returns

[`Bit`](README.md#bit)[]

___

### bytesToHex

▸ **bytesToHex**(`bytes`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bytes` | `Uint8Array` |

#### Returns

`string`

___

### bytesToString

▸ **bytesToString**(`bytes`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bytes` | `Uint8Array` |

#### Returns

`string`

___

### stringToBytes

▸ **stringToBytes**(`value`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `string` |

#### Returns

`Uint8Array`

___

### bytesToBase64

▸ **bytesToBase64**(`data`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Uint8Array` \| `number`[] |

#### Returns

`string`

___

### base64ToBytes

▸ **base64ToBytes**(`base64`): `Uint8Array`

#### Parameters

| Name | Type |
| :------ | :------ |
| `base64` | `string` |

#### Returns

`Uint8Array`

___

### sliceIntoChunks

▸ **sliceIntoChunks**(`arr`, `chunkSize`): `any`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `arr` | `any`[] |
| `chunkSize` | `number` |

#### Returns

`any`[]

## Properties

### bip0039en

• **bip0039en**: `string`[]
