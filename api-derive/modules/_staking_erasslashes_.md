[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["staking/erasSlashes"](_staking_erasslashes_.md)

# Module: "staking/erasSlashes"

## Index

### Functions

* [_erasSlashes](_staking_erasslashes_.md#_erasslashes)
* [eraSlashes](_staking_erasslashes_.md#eraslashes)
* [erasSlashes](_staking_erasslashes_.md#erasslashes)

## Functions

###  _erasSlashes

▸ **_erasSlashes**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/staking/erasSlashes.ts:42](https://github.com/polkadot-js/api/blob/174510a928/packages/api-derive/src/staking/erasSlashes.ts#L42)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

▸ (`eras`: EraIndex[]): *Observable‹DeriveEraSlashes[]›*

**Parameters:**

Name | Type |
------ | ------ |
`eras` | EraIndex[] |

___

###  eraSlashes

▸ **eraSlashes**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/staking/erasSlashes.ts:31](https://github.com/polkadot-js/api/blob/174510a928/packages/api-derive/src/staking/erasSlashes.ts#L31)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

▸ (`era`: EraIndex): *Observable‹DeriveEraSlashes›*

**Parameters:**

Name | Type |
------ | ------ |
`era` | EraIndex |

___

###  erasSlashes

▸ **erasSlashes**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/staking/erasSlashes.ts:52](https://github.com/polkadot-js/api/blob/174510a928/packages/api-derive/src/staking/erasSlashes.ts#L52)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

▸ (`withActive?`: undefined | false | true): *Observable‹DeriveEraSlashes[]›*

**Parameters:**

Name | Type |
------ | ------ |
`withActive?` | undefined &#124; false &#124; true |
