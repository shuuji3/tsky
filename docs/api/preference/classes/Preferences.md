[**preference**](../index.md)

***

[tsky](../../index.md) / [preference](../index.md) / Preferences

# Class: Preferences

## Constructors

### new Preferences()

> **new Preferences**(`instance`): [`Preferences`](Preferences.md)

#### Parameters

##### instance

`AppBskyNS`

#### Returns

[`Preferences`](Preferences.md)

#### Defined in

[preference.ts:8](https://github.com/anbraten/tsky/blob/d41f31ef5ffd7e02d6eae90f23a8982db2e99629/packages/core/src/preference.ts#L8)

## Methods

### get()

> **get**(`options`?): `Promise`\<`Preferences`\>

Get private preferences attached to the current account. Expected use is synchronization between multiple devices, and import/export during account migration. Requires auth.

#### Parameters

##### options?

`CallOptions`

#### Returns

`Promise`\<`Preferences`\>

#### Defined in

[preference.ts:13](https://github.com/anbraten/tsky/blob/d41f31ef5ffd7e02d6eae90f23a8982db2e99629/packages/core/src/preference.ts#L13)

***

### set()

> **set**(`preferences`, `options`?): `Promise`\<`void`\>

Set the private preferences attached to the account.

#### Parameters

##### preferences

`Preferences`

##### options?

`CallOptions`

#### Returns

`Promise`\<`void`\>

#### Defined in

[preference.ts:22](https://github.com/anbraten/tsky/blob/d41f31ef5ffd7e02d6eae90f23a8982db2e99629/packages/core/src/preference.ts#L22)