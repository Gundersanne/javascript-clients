[@redhat-cloud-services/osbuild-installer - v0.0.1](../README.md) › [Globals](../globals.md) › [MetaApi](metaapi.md)

# Class: MetaApi

MetaApi - object-oriented interface

**`export`** 

**`class`** MetaApi

**`extends`** {BaseAPI}

## Hierarchy

* [BaseAPI](baseapi.md)

  ↳ **MetaApi**

## Index

### Constructors

* [constructor](metaapi.md#constructor)

### Properties

* [axios](metaapi.md#protected-axios)
* [basePath](metaapi.md#protected-basepath)
* [configuration](metaapi.md#protected-configuration)

### Methods

* [getOpenapiJson](metaapi.md#getopenapijson)

## Constructors

###  constructor

\+ **new MetaApi**(`configuration?`: [Configuration](configuration.md), `basePath`: string, `axios`: AxiosInstance): *[MetaApi](metaapi.md)*

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [base.ts:49](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L49)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`configuration?` | [Configuration](configuration.md) | - |
`basePath` | string |  BASE_PATH |
`axios` | AxiosInstance |  globalAxios |

**Returns:** *[MetaApi](metaapi.md)*

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

###  getOpenapiJson

▸ **getOpenapiJson**(`options?`: any): *AxiosPromise‹void›*

*Defined in [api.ts:459](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/api.ts#L459)*

**`summary`** get the openapi json specification

**`throws`** {RequiredError}

**`memberof`** MetaApi

**Parameters:**

Name | Type |
------ | ------ |
`options?` | any |

**Returns:** *AxiosPromise‹void›*
