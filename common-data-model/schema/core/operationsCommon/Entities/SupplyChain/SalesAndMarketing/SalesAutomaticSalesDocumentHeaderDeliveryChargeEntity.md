---
title: SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Automatic sales document delivery charges

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Automatic sales document delivery charges</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ChargingCustomerAccountNumber](#ChargingCustomerAccountNumber)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[ChargingChargeCustomerGroupId](#ChargingChargeCustomerGroupId)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[ChargingDeliveryModeCode](#ChargingDeliveryModeCode)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[ChargingChargeDeliveryGroupId](#ChargingChargeDeliveryGroupId)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[LineNumber](#LineNumber)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[SalesDocumentCurrencyCode](#SalesDocumentCurrencyCode)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[DeliveryChargeCode](#DeliveryChargeCode)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[ChargeCategory](#ChargeCategory)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[ChargePercentage](#ChargePercentage)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[FixedChargeAmount](#FixedChargeAmount)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[ExternalChargeAmount](#ExternalChargeAmount)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[Value](#Value)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[ChargeAccountingCurrencyCode](#ChargeAccountingCurrencyCode)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[FromTotalLineAmount](#FromTotalLineAmount)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[ToTotalLineAmount](#ToTotalLineAmount)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[WillInvoiceProcessingKeepCharge](#WillInvoiceProcessingKeepCharge)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[AccountCode](#AccountCode)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[AccountRelation](#AccountRelation)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[DlvModeCode](#DlvModeCode)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[DlvModeRelation](#DlvModeRelation)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[BackingTable_MarkupAutoLineRelationshipId](#BackingTable_MarkupAutoLineRelationshipId)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity.md" target="_blank">SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity</a>|

### <a href=#ChargingCustomerAccountNumber name="ChargingCustomerAccountNumber">ChargingCustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargingCustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargingChargeCustomerGroupId name="ChargingChargeCustomerGroupId">ChargingChargeCustomerGroupId</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargingChargeCustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargingDeliveryModeCode name="ChargingDeliveryModeCode">ChargingDeliveryModeCode</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargingDeliveryModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargingChargeDeliveryGroupId name="ChargingChargeDeliveryGroupId">ChargingChargeDeliveryGroupId</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargingChargeDeliveryGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesDocumentCurrencyCode name="SalesDocumentCurrencyCode">SalesDocumentCurrencyCode</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesDocumentCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryChargeCode name="DeliveryChargeCode">DeliveryChargeCode</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryChargeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeCategory name="ChargeCategory">ChargeCategory</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargePercentage name="ChargePercentage">ChargePercentage</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedChargeAmount name="FixedChargeAmount">FixedChargeAmount</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalChargeAmount name="ExternalChargeAmount">ExternalChargeAmount</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Value name="Value">Value</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Value attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeAccountingCurrencyCode name="ChargeAccountingCurrencyCode">ChargeAccountingCurrencyCode</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeAccountingCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromTotalLineAmount name="FromTotalLineAmount">FromTotalLineAmount</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromTotalLineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToTotalLineAmount name="ToTotalLineAmount">ToTotalLineAmount</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToTotalLineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillInvoiceProcessingKeepCharge name="WillInvoiceProcessingKeepCharge">WillInvoiceProcessingKeepCharge</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillInvoiceProcessingKeepCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountCode name="AccountCode">AccountCode</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountRelation name="AccountRelation">AccountRelation</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DlvModeCode name="DlvModeCode">DlvModeCode</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DlvModeRelation name="DlvModeRelation">DlvModeRelation</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvModeRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_MarkupAutoLineRelationshipId name="BackingTable_MarkupAutoLineRelationshipId">BackingTable_MarkupAutoLineRelationshipId</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_MarkupAutoLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/MarkupAutoLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/MarkupAutoLine.cdm.json/MarkupAutoLine</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/MarkupAutoLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesAutomaticSalesDocumentHeaderDeliveryChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>