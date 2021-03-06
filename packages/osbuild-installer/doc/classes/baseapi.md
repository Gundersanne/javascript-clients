[@redhat-cloud-services/osbuild-installer - v0.0.1](../README.md) › [Globals](../globals.md) › [BaseAPI](baseapi.md)

# Class: BaseAPI

**`export`** 

**`class`** BaseAPI

## Hierarchy

* **BaseAPI**

  ↳ [DefaultApi](defaultapi.md)

  ↳ [MetaApi](metaapi.md)

## Index

### Constructors

* [constructor](baseapi.md#constructor)

### Properties

* [axios](baseapi.md#protected-axios)
* [basePath](baseapi.md#protected-basepath)
* [configuration](baseapi.md#protected-configuration)

## Constructors

###  constructor

\+ **new BaseAPI**(`configuration?`: [Configuration](configuration.md), `basePath`: string, `axios`: AxiosInstance): *[BaseAPI](baseapi.md)*

*Defined in [base.ts:49](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L49)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`configuration?` | [Configuration](configuration.md) | - |
`basePath` | string |  BASE_PATH |
`axios` | AxiosInstance |  globalAxios |

**Returns:** *[BaseAPI](baseapi.md)*

## Properties

### `Protected` axios

• **axios**: *AxiosInstance*

*Defined in [base.ts:51](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L51)*

___

### `Protected` basePath

• **basePath**: *string*

*Defined in [base.ts:51](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L51)*

___

### `Protected` configuration

• **configuration**: *[Configuration](configuration.md) | undefined*

*Defined in [base.ts:49](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/base.ts#L49)*
