[@redhat-cloud-services/remediations-client](../README.md) › [Globals](../globals.md) › [RemediationListLinks](remediationlistlinks.md)

# Interface: RemediationListLinks

**`export`** 

**`interface`** RemediationListLinks

## Hierarchy

* **RemediationListLinks**

## Index

### Properties

* [first](remediationlistlinks.md#first)
* [last](remediationlistlinks.md#last)
* [next](remediationlistlinks.md#next)
* [previous](remediationlistlinks.md#previous)

## Properties

###  first

• **first**: *string*

*Defined in [api.ts:930](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L930)*

relative link to the first page of the query results

**`type`** {string}

**`memberof`** RemediationListLinks

___

###  last

• **last**: *string*

*Defined in [api.ts:936](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L936)*

relative link to the last page of the query results

**`type`** {string}

**`memberof`** RemediationListLinks

___

###  next

• **next**: *string | null*

*Defined in [api.ts:942](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L942)*

relative link to the next page of the query results (or null if this is the last page)

**`type`** {string}

**`memberof`** RemediationListLinks

___

###  previous

• **previous**: *string | null*

*Defined in [api.ts:948](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/remediations/api.ts#L948)*

relative link to the previous page of the query results (or null if this is the first page)

**`type`** {string}

**`memberof`** RemediationListLinks
