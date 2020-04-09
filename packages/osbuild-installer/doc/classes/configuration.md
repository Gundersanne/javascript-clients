[@redhat-cloud-services/osbuild-installer - v0.0.1](../README.md) › [Globals](../globals.md) › [Configuration](configuration.md)

# Class: Configuration

## Hierarchy

* **Configuration**

## Index

### Constructors

* [constructor](configuration.md#constructor)

### Properties

* [accessToken](configuration.md#optional-accesstoken)
* [apiKey](configuration.md#optional-apikey)
* [baseOptions](configuration.md#optional-baseoptions)
* [basePath](configuration.md#optional-basepath)
* [password](configuration.md#optional-password)
* [username](configuration.md#optional-username)

## Constructors

###  constructor

\+ **new Configuration**(`param`: [ConfigurationParameters](../interfaces/configurationparameters.md)): *[Configuration](configuration.md)*

*Defined in [configuration.ts:65](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/configuration.ts#L65)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`param` | [ConfigurationParameters](../interfaces/configurationparameters.md) |  {} |

**Returns:** *[Configuration](configuration.md)*

## Properties

### `Optional` accessToken

• **accessToken**? : *string | function*

*Defined in [configuration.ts:51](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/configuration.ts#L51)*

parameter for oauth2 security

**`param`** security name

**`param`** oauth2 scope

**`memberof`** Configuration

___

### `Optional` apiKey

• **apiKey**? : *string | function*

*Defined in [configuration.ts:30](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/configuration.ts#L30)*

parameter for apiKey security

**`param`** security name

**`memberof`** Configuration

___

### `Optional` baseOptions

• **baseOptions**? : *any*

*Defined in [configuration.ts:65](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/configuration.ts#L65)*

base options for axios calls

**`type`** {any}

**`memberof`** Configuration

___

### `Optional` basePath

• **basePath**? : *string*

*Defined in [configuration.ts:58](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/configuration.ts#L58)*

override base path

**`type`** {string}

**`memberof`** Configuration

___

### `Optional` password

• **password**? : *string*

*Defined in [configuration.ts:44](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/configuration.ts#L44)*

parameter for basic security

**`type`** {string}

**`memberof`** Configuration

___

### `Optional` username

• **username**? : *string*

*Defined in [configuration.ts:37](https://github.com/Gundersanne/javascript-clients/blob/master/packages/osbuild-installer/configuration.ts#L37)*

parameter for basic security

**`type`** {string}

**`memberof`** Configuration