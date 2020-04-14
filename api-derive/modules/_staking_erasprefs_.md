[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["staking/erasPrefs"](_staking_erasprefs_.md)

# Module: "staking/erasPrefs"

## Index

### Functions

* [_erasPrefs](_staking_erasprefs_.md#_erasprefs)
* [eraPrefs](_staking_erasprefs_.md#eraprefs)
* [erasPrefs](_staking_erasprefs_.md#erasprefs)

## Functions

###  _erasPrefs

▸ **_erasPrefs**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/staking/erasPrefs.ts:33](https://github.com/polkadot-js/api/blob/9387103558/packages/api-derive/src/staking/erasPrefs.ts#L33)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

▸ (`eras`: EraIndex[]): *Observable‹DeriveEraPrefs[]›*

**Parameters:**

Name | Type |
------ | ------ |
`eras` | EraIndex[] |

___

###  eraPrefs

▸ **eraPrefs**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/staking/erasPrefs.ts:25](https://github.com/polkadot-js/api/blob/9387103558/packages/api-derive/src/staking/erasPrefs.ts#L25)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

▸ (`era`: EraIndex): *Observable‹DeriveEraPrefs›*

**Parameters:**

Name | Type |
------ | ------ |
`era` | EraIndex |

___

###  erasPrefs

▸ **erasPrefs**(`api`: ApiInterfaceRx): *function*

*Defined in [packages/api-derive/src/staking/erasPrefs.ts:41](https://github.com/polkadot-js/api/blob/9387103558/packages/api-derive/src/staking/erasPrefs.ts#L41)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiInterfaceRx |

**Returns:** *function*

▸ (`withActive?`: undefined | false | true): *Observable‹DeriveEraPrefs[]›*

**Parameters:**

Name | Type |
------ | ------ |
`withActive?` | undefined &#124; false &#124; true |
