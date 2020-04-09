[@redhat-cloud-services/osbuild-installer - v0.0.1](README.md) › [Globals](globals.md)

# @redhat-cloud-services/osbuild-installer - v0.0.1

## Index

### Classes

* [BaseAPI](classes/baseapi.md)
* [Configuration](classes/configuration.md)
* [DefaultApi](classes/defaultapi.md)
* [MetaApi](classes/metaapi.md)
* [RequiredError](classes/requirederror.md)

### Interfaces

* [Compose](interfaces/compose.md)
* [ComposeRequest](interfaces/composerequest.md)
* [ComposeResponse](interfaces/composeresponse.md)
* [ComposeStatus](interfaces/composestatus.md)
* [ConfigurationParameters](interfaces/configurationparameters.md)
* [Repository](interfaces/repository.md)
* [RequestArgs](interfaces/requestargs.md)
* [Version](interfaces/version.md)

### Variables

* [BASE_PATH](globals.md#const-base_path)

### Functions

* [DefaultApiAxiosParamCreator](globals.md#const-defaultapiaxiosparamcreator)
* [DefaultApiFactory](globals.md#const-defaultapifactory)
* [DefaultApiFp](globals.md#const-defaultapifp)
* [MetaApiAxiosParamCreator](globals.md#const-metaapiaxiosparamcreator)
* [MetaApiFactory](globals.md#const-metaapifactory)
* [MetaApiFp](globals.md#const-metaapifp)

### Object literals

* [COLLECTION_FORMATS](globals.md#const-collection_formats)

## Variables

### `Const` BASE_PATH

• **BASE_PATH**: *string* =  "https://prod.foo.redhat.com:13338/api/osbuild-installer/v1".replace(/\/+$/, "")

*Defined in [base.ts:20](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L20)*

## Functions

### `Const` DefaultApiAxiosParamCreator

▸ **DefaultApiAxiosParamCreator**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [api.ts:123](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/api.ts#L123)*

DefaultApi - axios parameter creator

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **composeImage**(`composeRequest`: [ComposeRequest](interfaces/composerequest.md), `options`: any): *[RequestArgs](interfaces/requestargs.md)*

* **getComposeStatus**(`composeId`: string, `options`: any): *[RequestArgs](interfaces/requestargs.md)*

* **getVersion**(`options`: any): *[RequestArgs](interfaces/requestargs.md)*

___

### `Const` DefaultApiFactory

▸ **DefaultApiFactory**(`configuration?`: [Configuration](classes/configuration.md), `basePath?`: string, `axios?`: AxiosInstance): *object*

*Defined in [api.ts:287](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/api.ts#L287)*

DefaultApi - factory interface

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |
`basePath?` | string |
`axios?` | AxiosInstance |

**Returns:** *object*

* **composeImage**(`composeRequest`: [ComposeRequest](interfaces/composerequest.md), `options?`: any): *AxiosPromise‹[ComposeResponse](interfaces/composeresponse.md)›*

* **getComposeStatus**(`composeId`: string, `options?`: any): *AxiosPromise‹[ComposeStatus](interfaces/composestatus.md)›*

* **getVersion**(`options?`: any): *AxiosPromise‹[Version](interfaces/version.md)›*

___

### `Const` DefaultApiFp

▸ **DefaultApiFp**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [api.ts:237](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/api.ts#L237)*

DefaultApi - functional programming interface

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **composeImage**(`composeRequest`: [ComposeRequest](interfaces/composerequest.md), `options?`: any): *function*

  * (`axios?`: AxiosInstance, `basePath?`: string): *AxiosPromise‹[ComposeResponse](interfaces/composeresponse.md)›*

* **getComposeStatus**(`composeId`: string, `options?`: any): *function*

  * (`axios?`: AxiosInstance, `basePath?`: string): *AxiosPromise‹[ComposeStatus](interfaces/composestatus.md)›*

* **getVersion**(`options?`: any): *function*

  * (`axios?`: AxiosInstance, `basePath?`: string): *AxiosPromise‹[Version](interfaces/version.md)›*

___

### `Const` MetaApiAxiosParamCreator

▸ **MetaApiAxiosParamCreator**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [api.ts:370](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/api.ts#L370)*

MetaApi - axios parameter creator

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **getOpenapiJson**(`options`: any): *[RequestArgs](interfaces/requestargs.md)*

___

### `Const` MetaApiFactory

▸ **MetaApiFactory**(`configuration?`: [Configuration](classes/configuration.md), `basePath?`: string, `axios?`: AxiosInstance): *object*

*Defined in [api.ts:431](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/api.ts#L431)*

MetaApi - factory interface

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |
`basePath?` | string |
`axios?` | AxiosInstance |

**Returns:** *object*

* **getOpenapiJson**(`options?`: any): *AxiosPromise‹void›*

___

### `Const` MetaApiFp

▸ **MetaApiFp**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [api.ts:409](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/api.ts#L409)*

MetaApi - functional programming interface

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **getOpenapiJson**(`options?`: any): *function*

  * (`axios?`: AxiosInstance, `basePath?`: string): *AxiosPromise‹void›*

## Object literals

### `Const` COLLECTION_FORMATS

### ▪ **COLLECTION_FORMATS**: *object*

*Defined in [base.ts:26](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L26)*

**`export`** 

###  csv

• **csv**: *string* = ","

*Defined in [base.ts:27](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L27)*

###  pipes

• **pipes**: *string* = "|"

*Defined in [base.ts:30](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L30)*

###  ssv

• **ssv**: *string* = " "

*Defined in [base.ts:28](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L28)*

###  tsv

• **tsv**: *string* = "	"

*Defined in [base.ts:29](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L29)*
