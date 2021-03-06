[@redhat-cloud-services/vulnerabilities-client](../README.md) › [Globals](../globals.md) › [MetaCvesSystems](metacvessystems.md)

# Interface: MetaCvesSystems

**`export`** 

**`interface`** MetaCvesSystems

## Hierarchy

* **MetaCvesSystems**

## Index

### Properties

* [businessRiskId](metacvessystems.md#businessriskid)
* [cvssFrom](metacvessystems.md#cvssfrom)
* [cvssTo](metacvessystems.md#cvssto)
* [dataFormat](metacvessystems.md#dataformat)
* [filter](metacvessystems.md#filter)
* [impact](metacvessystems.md#impact)
* [limit](metacvessystems.md#limit)
* [offset](metacvessystems.md#offset)
* [optOut](metacvessystems.md#optout)
* [page](metacvessystems.md#page)
* [pageSize](metacvessystems.md#pagesize)
* [pages](metacvessystems.md#pages)
* [publicFrom](metacvessystems.md#publicfrom)
* [publicTo](metacvessystems.md#publicto)
* [sort](metacvessystems.md#sort)
* [statusId](metacvessystems.md#statusid)
* [totalItems](metacvessystems.md#totalitems)

## Properties

###  businessRiskId

• **businessRiskId**: *string | null*

*Defined in [api.ts:949](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L949)*

Filter based on business risk IDs.

**`type`** {string}

**`memberof`** MetaCvesSystems

___

###  cvssFrom

• **cvssFrom**: *number | null*

*Defined in [api.ts:955](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L955)*

Filter based on cvss score, starting from the value.

**`type`** {number}

**`memberof`** MetaCvesSystems

___

###  cvssTo

• **cvssTo**: *number | null*

*Defined in [api.ts:961](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L961)*

Filter based on cvss score, up to the value.

**`type`** {number}

**`memberof`** MetaCvesSystems

___

###  dataFormat

• **dataFormat**: *string*

*Defined in [api.ts:943](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L943)*

Format of the output data, either JSON (default) or CSV.

**`type`** {string}

**`memberof`** MetaCvesSystems

___

###  filter

• **filter**: *string | null*

*Defined in [api.ts:895](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L895)*

Full text filter

**`type`** {string}

**`memberof`** MetaCvesSystems

___

###  impact

• **impact**: *string | null*

*Defined in [api.ts:979](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L979)*

Filter based on impact IDs.

**`type`** {string}

**`memberof`** MetaCvesSystems

___

###  limit

• **limit**: *number*

*Defined in [api.ts:901](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L901)*

Maximum number of paginated results.

**`type`** {number}

**`memberof`** MetaCvesSystems

___

###  offset

• **offset**: *number*

*Defined in [api.ts:907](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L907)*

First record of paginated response.

**`type`** {number}

**`memberof`** MetaCvesSystems

___

###  optOut

• **optOut**: *boolean*

*Defined in [api.ts:991](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L991)*

If given system was opted out.

**`type`** {boolean}

**`memberof`** MetaCvesSystems

___

###  page

• **page**: *number*

*Defined in [api.ts:913](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L913)*

Page number of paginated response.

**`type`** {number}

**`memberof`** MetaCvesSystems

___

###  pageSize

• **pageSize**: *number*

*Defined in [api.ts:919](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L919)*

Number of records per page of paginated response.

**`type`** {number}

**`memberof`** MetaCvesSystems

___

###  pages

• **pages**: *number*

*Defined in [api.ts:925](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L925)*

Total number of pages of paginated response.

**`type`** {number}

**`memberof`** MetaCvesSystems

___

###  publicFrom

• **publicFrom**: *string | null*

*Defined in [api.ts:967](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L967)*

Filter CVEs based on their published date, starting from the date.

**`type`** {string}

**`memberof`** MetaCvesSystems

___

###  publicTo

• **publicTo**: *string | null*

*Defined in [api.ts:973](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L973)*

Filter CVEs based on their published date, up to the date.

**`type`** {string}

**`memberof`** MetaCvesSystems

___

###  sort

• **sort**: *string | null*

*Defined in [api.ts:931](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L931)*

Sorting filter.

**`type`** {string}

**`memberof`** MetaCvesSystems

___

###  statusId

• **statusId**: *string | null*

*Defined in [api.ts:985](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L985)*

Filer based on CVE status ID.

**`type`** {string}

**`memberof`** MetaCvesSystems

___

###  totalItems

• **totalItems**: *number*

*Defined in [api.ts:937](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/api.ts#L937)*

Total number of records.

**`type`** {number}

**`memberof`** MetaCvesSystems
