[@redhat-cloud-services/catalog-client](../README.md) › [Globals](../globals.md) › [SharePolicy](sharepolicy.md)

# Module: SharePolicy

**`export`** 

**`namespace`** SharePolicy

## Index

### Enumerations

* [PermissionsEnum](../enums/sharepolicy.permissionsenum.md)

### Properties

* [groupUuids](sharepolicy.md#groupuuids)
* [permissions](sharepolicy.md#permissions)

## Properties

###  groupUuids

• **groupUuids**: *Array‹string›*

*Defined in [api.ts:1067](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L1067)*

An array of group UUID's retrieved from the RBAC Service with whom the resource has to be shared.

**`type`** {Array<string>}

**`memberof`** SharePolicy

___

###  permissions

• **permissions**: *Array‹[PermissionsEnum](../enums/sharepolicy.permissionsenum.md)›*

*Defined in [api.ts:1061](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/catalog/api.ts#L1061)*

The permissions to apply for this share. The valid values are read, update, delete and order

**`type`** {Array<string>}

**`memberof`** SharePolicy
