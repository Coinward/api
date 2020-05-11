[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["types/extrinsic"](../modules/_types_extrinsic_.md) › [Signer](_types_extrinsic_.signer.md)

# Interface: Signer

## Hierarchy

* **Signer**

## Index

### Properties

* [signPayload](_types_extrinsic_.signer.md#optional-signpayload)
* [signRaw](_types_extrinsic_.signer.md#optional-signraw)
* [update](_types_extrinsic_.signer.md#optional-update)

## Properties

### `Optional` signPayload

• **signPayload**? : *undefined | function*

*Defined in [packages/types/src/types/extrinsic.ts:44](https://github.com/polkadot-js/api/blob/8491ab8ca6/packages/types/src/types/extrinsic.ts#L44)*

**`description`** signs an extrinsic payload from a serialized form

___

### `Optional` signRaw

• **signRaw**? : *undefined | function*

*Defined in [packages/types/src/types/extrinsic.ts:49](https://github.com/polkadot-js/api/blob/8491ab8ca6/packages/types/src/types/extrinsic.ts#L49)*

**`description`** signs a raw payload, only the bytes data as supplied

___

### `Optional` update

• **update**? : *undefined | function*

*Defined in [packages/types/src/types/extrinsic.ts:54](https://github.com/polkadot-js/api/blob/8491ab8ca6/packages/types/src/types/extrinsic.ts#L54)*

**`description`** Receives an update for the extrinsic signed by a `signer.sign`
