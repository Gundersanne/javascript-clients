[@redhat-cloud-services/insights-client](../README.md) › [Globals](../globals.md) › [TotalRiskApi](totalriskapi.md)

# Class: TotalRiskApi

TotalRiskApi - object-oriented interface

**`export`** 

**`class`** TotalRiskApi

**`extends`** {BaseAPI}

## Hierarchy

* [BaseAPI](baseapi.md)

  ↳ **TotalRiskApi**

## Index

### Constructors

* [constructor](totalriskapi.md#constructor)

### Properties

* [axios](totalriskapi.md#protected-axios)
* [basePath](totalriskapi.md#protected-basepath)
* [configuration](totalriskapi.md#protected-configuration)

### Methods

* [totalRiskList](totalriskapi.md#totalrisklist)

## Constructors

###  constructor

\+ **new TotalRiskApi**(`configuration?`: [Configuration](configuration.md), `basePath`: string, `axios`: AxiosInstance): *[TotalRiskApi](totalriskapi.md)*

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [api.ts:49](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L49)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`configuration?` | [Configuration](configuration.md) | - |
`basePath` | string |  BASE_PATH |
`axios` | AxiosInstance |  globalAxios |

**Returns:** *[TotalRiskApi](totalriskapi.md)*

## Properties

### `Protected` axios

• **axios**: *AxiosInstance*

*Inherited from [BaseAPI](baseapi.md).[axios](baseapi.md#protected-axios)*

*Defined in [api.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L51)*

___

### `Protected` basePath

• **basePath**: *string*

*Inherited from [BaseAPI](baseapi.md).[basePath](baseapi.md#protected-basepath)*

*Defined in [api.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L51)*

___

### `Protected` configuration

• **configuration**: *[Configuration](configuration.md) | undefined*

*Inherited from [BaseAPI](baseapi.md).[configuration](baseapi.md#protected-configuration)*

*Defined in [api.ts:49](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L49)*

## Methods

###  totalRiskList

▸ **totalRiskList**(`options?`: any): *AxiosPromise‹Response›*

*Defined in [api.ts:5394](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L5394)*

Total risk values are listed in increasing order of severity.

**`summary`** List all total risk values.

**`throws`** {RequiredError}

**`memberof`** TotalRiskApi

**Parameters:**

Name | Type |
------ | ------ |
`options?` | any |

**Returns:** *AxiosPromise‹Response›*
