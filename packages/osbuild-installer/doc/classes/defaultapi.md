[@redhat-cloud-services/osbuild-installer - v0.0.1](../README.md) › [Globals](../globals.md) › [DefaultApi](defaultapi.md)

# Class: DefaultApi

DefaultApi - object-oriented interface

**`export`** 

**`class`** DefaultApi

**`extends`** {BaseAPI}

## Hierarchy

* [BaseAPI](baseapi.md)

  ↳ **DefaultApi**

## Index

### Constructors

* [constructor](defaultapi.md#constructor)

### Properties

* [axios](defaultapi.md#protected-axios)
* [basePath](defaultapi.md#protected-basepath)
* [configuration](defaultapi.md#protected-configuration)

### Methods

* [composeImage](defaultapi.md#composeimage)
* [getComposeStatus](defaultapi.md#getcomposestatus)
* [getVersion](defaultapi.md#getversion)

## Constructors

###  constructor

\+ **new DefaultApi**(`configuration?`: [Configuration](configuration.md), `basePath`: string, `axios`: AxiosInstance): *[DefaultApi](defaultapi.md)*

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [base.ts:49](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L49)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`configuration?` | [Configuration](configuration.md) | - |
`basePath` | string |  BASE_PATH |
`axios` | AxiosInstance |  globalAxios |

**Returns:** *[DefaultApi](defaultapi.md)*

## Properties

### `Protected` axios

• **axios**: *AxiosInstance*

*Inherited from [BaseAPI](baseapi.md).[axios](baseapi.md#protected-axios)*

*Defined in [base.ts:51](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L51)*

___

### `Protected` basePath

• **basePath**: *string*

*Inherited from [BaseAPI](baseapi.md).[basePath](baseapi.md#protected-basepath)*

*Defined in [base.ts:51](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L51)*

___

### `Protected` configuration

• **configuration**: *[Configuration](configuration.md) | undefined*

*Inherited from [BaseAPI](baseapi.md).[configuration](baseapi.md#protected-configuration)*

*Defined in [base.ts:49](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L49)*

## Methods

###  composeImage

▸ **composeImage**(`composeRequest`: [ComposeRequest](../interfaces/composerequest.md), `options?`: any): *AxiosPromise‹[ComposeResponse](../interfaces/composeresponse.md)›*

*Defined in [api.ts:336](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/api.ts#L336)*

compose image

**`summary`** compose image

**`throws`** {RequiredError}

**`memberof`** DefaultApi

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`composeRequest` | [ComposeRequest](../interfaces/composerequest.md) | details of image to be composed |
`options?` | any | - |

**Returns:** *AxiosPromise‹[ComposeResponse](../interfaces/composeresponse.md)›*

___

###  getComposeStatus

▸ **getComposeStatus**(`composeId`: string, `options?`: any): *AxiosPromise‹[ComposeStatus](../interfaces/composestatus.md)›*

*Defined in [api.ts:348](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/api.ts#L348)*

status of an image compose

**`summary`** get status of an image compose

**`throws`** {RequiredError}

**`memberof`** DefaultApi

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`composeId` | string | Id of compose status to get |
`options?` | any | - |

**Returns:** *AxiosPromise‹[ComposeStatus](../interfaces/composestatus.md)›*

___

###  getVersion

▸ **getVersion**(`options?`: any): *AxiosPromise‹[Version](../interfaces/version.md)›*

*Defined in [api.ts:359](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/api.ts#L359)*

get the service version

**`summary`** get the service version

**`throws`** {RequiredError}

**`memberof`** DefaultApi

**Parameters:**

Name | Type |
------ | ------ |
`options?` | any |

**Returns:** *AxiosPromise‹[Version](../interfaces/version.md)›*
