[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["types/extrinsic"](../modules/_types_extrinsic_.md) › [SignerPayloadJSON](_types_extrinsic_.signerpayloadjson.md)

# Interface: SignerPayloadJSON

## Hierarchy

* **SignerPayloadJSON**

## Index

### Properties

* [address](_types_extrinsic_.signerpayloadjson.md#address)
* [blockHash](_types_extrinsic_.signerpayloadjson.md#blockhash)
* [blockNumber](_types_extrinsic_.signerpayloadjson.md#blocknumber)
* [era](_types_extrinsic_.signerpayloadjson.md#era)
* [genesisHash](_types_extrinsic_.signerpayloadjson.md#genesishash)
* [method](_types_extrinsic_.signerpayloadjson.md#method)
* [nonce](_types_extrinsic_.signerpayloadjson.md#nonce)
* [specVersion](_types_extrinsic_.signerpayloadjson.md#specversion)
* [tip](_types_extrinsic_.signerpayloadjson.md#tip)
* [version](_types_extrinsic_.signerpayloadjson.md#version)

## Properties

###  address

• **address**: *string*

*Defined in [packages/types/src/types/extrinsic.ts:125](https://github.com/polkadot-js/api/blob/d3d3bb9b5a/packages/types/src/types/extrinsic.ts#L125)*

**`description`** The ss-58 encoded address

___

###  blockHash

• **blockHash**: *string*

*Defined in [packages/types/src/types/extrinsic.ts:130](https://github.com/polkadot-js/api/blob/d3d3bb9b5a/packages/types/src/types/extrinsic.ts#L130)*

**`description`** The checkpoint hash of the block, in hex

___

###  blockNumber

• **blockNumber**: *string*

*Defined in [packages/types/src/types/extrinsic.ts:135](https://github.com/polkadot-js/api/blob/d3d3bb9b5a/packages/types/src/types/extrinsic.ts#L135)*

**`description`** The checkpoint block number, in hex

___

###  era

• **era**: *string*

*Defined in [packages/types/src/types/extrinsic.ts:140](https://github.com/polkadot-js/api/blob/d3d3bb9b5a/packages/types/src/types/extrinsic.ts#L140)*

**`description`** The era for this transaction, in hex

___

###  genesisHash

• **genesisHash**: *string*

*Defined in [packages/types/src/types/extrinsic.ts:145](https://github.com/polkadot-js/api/blob/d3d3bb9b5a/packages/types/src/types/extrinsic.ts#L145)*

**`description`** The genesis hash of the chain, in hex

___

###  method

• **method**: *string*

*Defined in [packages/types/src/types/extrinsic.ts:150](https://github.com/polkadot-js/api/blob/d3d3bb9b5a/packages/types/src/types/extrinsic.ts#L150)*

**`description`** The encoded method (with arguments) in hex

___

###  nonce

• **nonce**: *string*

*Defined in [packages/types/src/types/extrinsic.ts:155](https://github.com/polkadot-js/api/blob/d3d3bb9b5a/packages/types/src/types/extrinsic.ts#L155)*

**`description`** The nonce for this transaction, in hex

___

###  specVersion

• **specVersion**: *string*

*Defined in [packages/types/src/types/extrinsic.ts:160](https://github.com/polkadot-js/api/blob/d3d3bb9b5a/packages/types/src/types/extrinsic.ts#L160)*

**`description`** The current spec version for  the runtime

___

###  tip

• **tip**: *string*

*Defined in [packages/types/src/types/extrinsic.ts:165](https://github.com/polkadot-js/api/blob/d3d3bb9b5a/packages/types/src/types/extrinsic.ts#L165)*

**`description`** The tip for this transaction, in hex

___

###  version

• **version**: *number*

*Defined in [packages/types/src/types/extrinsic.ts:170](https://github.com/polkadot-js/api/blob/d3d3bb9b5a/packages/types/src/types/extrinsic.ts#L170)*

**`description`** The version of the extrinsic we are dealing with
