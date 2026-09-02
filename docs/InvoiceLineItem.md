# InvoiceLineItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArticleNumber** | Pointer to **NullableString** |  | [optional] 
**Description** | **string** |  | 
**DiscountAmount** | Pointer to **NullableString** |  | [optional] 
**DiscountPercentage** | Pointer to **NullableString** |  | [optional] 
**InputVatDeductible** | Pointer to **NullableBool** |  | [optional] 
**InputVatRate** | Pointer to **NullableString** |  | [optional] 
**IsIntraCommunityAcquisition** | Pointer to **NullableBool** |  | [optional] 
**IsMargin25a** | Pointer to **NullableBool** |  | [optional] 
**LedgerAccount** | Pointer to **NullableString** |  | [optional] 
**LineTotal** | **string** |  | 
**LineTotalGross** | Pointer to **NullableString** |  | [optional] 
**Margin25aPurchasePrice** | Pointer to **NullableString** |  | [optional] 
**MeterPointId** | Pointer to **NullableString** |  | [optional] 
**Position** | **int64** |  | 
**PriceComponents** | Pointer to **interface{}** |  | [optional] 
**ProductId** | Pointer to **NullableString** |  | [optional] 
**ProductSku** | Pointer to **NullableString** |  | [optional] 
**Quantity** | **string** |  | 
**SupplierArticleNumber** | Pointer to **NullableString** |  | [optional] 
**TaxRate** | Pointer to **NullableString** |  | [optional] 
**Unit** | **interface{}** |  | 
**UnitPrice** | **string** |  | 
**UsageDataId** | Pointer to **NullableString** |  | [optional] 
**VatRateNominal** | Pointer to **NullableString** |  | [optional] 
**VatSpecialCase** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewInvoiceLineItem

`func NewInvoiceLineItem(description string, lineTotal string, position int64, quantity string, unit interface{}, unitPrice string, ) *InvoiceLineItem`

NewInvoiceLineItem instantiates a new InvoiceLineItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceLineItemWithDefaults

`func NewInvoiceLineItemWithDefaults() *InvoiceLineItem`

NewInvoiceLineItemWithDefaults instantiates a new InvoiceLineItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArticleNumber

`func (o *InvoiceLineItem) GetArticleNumber() string`

GetArticleNumber returns the ArticleNumber field if non-nil, zero value otherwise.

### GetArticleNumberOk

`func (o *InvoiceLineItem) GetArticleNumberOk() (*string, bool)`

GetArticleNumberOk returns a tuple with the ArticleNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArticleNumber

`func (o *InvoiceLineItem) SetArticleNumber(v string)`

SetArticleNumber sets ArticleNumber field to given value.

### HasArticleNumber

`func (o *InvoiceLineItem) HasArticleNumber() bool`

HasArticleNumber returns a boolean if a field has been set.

### SetArticleNumberNil

`func (o *InvoiceLineItem) SetArticleNumberNil(b bool)`

 SetArticleNumberNil sets the value for ArticleNumber to be an explicit nil

### UnsetArticleNumber
`func (o *InvoiceLineItem) UnsetArticleNumber()`

UnsetArticleNumber ensures that no value is present for ArticleNumber, not even an explicit nil
### GetDescription

`func (o *InvoiceLineItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *InvoiceLineItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *InvoiceLineItem) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetDiscountAmount

`func (o *InvoiceLineItem) GetDiscountAmount() string`

GetDiscountAmount returns the DiscountAmount field if non-nil, zero value otherwise.

### GetDiscountAmountOk

`func (o *InvoiceLineItem) GetDiscountAmountOk() (*string, bool)`

GetDiscountAmountOk returns a tuple with the DiscountAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountAmount

`func (o *InvoiceLineItem) SetDiscountAmount(v string)`

SetDiscountAmount sets DiscountAmount field to given value.

### HasDiscountAmount

`func (o *InvoiceLineItem) HasDiscountAmount() bool`

HasDiscountAmount returns a boolean if a field has been set.

### SetDiscountAmountNil

`func (o *InvoiceLineItem) SetDiscountAmountNil(b bool)`

 SetDiscountAmountNil sets the value for DiscountAmount to be an explicit nil

### UnsetDiscountAmount
`func (o *InvoiceLineItem) UnsetDiscountAmount()`

UnsetDiscountAmount ensures that no value is present for DiscountAmount, not even an explicit nil
### GetDiscountPercentage

`func (o *InvoiceLineItem) GetDiscountPercentage() string`

GetDiscountPercentage returns the DiscountPercentage field if non-nil, zero value otherwise.

### GetDiscountPercentageOk

`func (o *InvoiceLineItem) GetDiscountPercentageOk() (*string, bool)`

GetDiscountPercentageOk returns a tuple with the DiscountPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountPercentage

`func (o *InvoiceLineItem) SetDiscountPercentage(v string)`

SetDiscountPercentage sets DiscountPercentage field to given value.

### HasDiscountPercentage

`func (o *InvoiceLineItem) HasDiscountPercentage() bool`

HasDiscountPercentage returns a boolean if a field has been set.

### SetDiscountPercentageNil

`func (o *InvoiceLineItem) SetDiscountPercentageNil(b bool)`

 SetDiscountPercentageNil sets the value for DiscountPercentage to be an explicit nil

### UnsetDiscountPercentage
`func (o *InvoiceLineItem) UnsetDiscountPercentage()`

UnsetDiscountPercentage ensures that no value is present for DiscountPercentage, not even an explicit nil
### GetInputVatDeductible

`func (o *InvoiceLineItem) GetInputVatDeductible() bool`

GetInputVatDeductible returns the InputVatDeductible field if non-nil, zero value otherwise.

### GetInputVatDeductibleOk

`func (o *InvoiceLineItem) GetInputVatDeductibleOk() (*bool, bool)`

GetInputVatDeductibleOk returns a tuple with the InputVatDeductible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputVatDeductible

`func (o *InvoiceLineItem) SetInputVatDeductible(v bool)`

SetInputVatDeductible sets InputVatDeductible field to given value.

### HasInputVatDeductible

`func (o *InvoiceLineItem) HasInputVatDeductible() bool`

HasInputVatDeductible returns a boolean if a field has been set.

### SetInputVatDeductibleNil

`func (o *InvoiceLineItem) SetInputVatDeductibleNil(b bool)`

 SetInputVatDeductibleNil sets the value for InputVatDeductible to be an explicit nil

### UnsetInputVatDeductible
`func (o *InvoiceLineItem) UnsetInputVatDeductible()`

UnsetInputVatDeductible ensures that no value is present for InputVatDeductible, not even an explicit nil
### GetInputVatRate

`func (o *InvoiceLineItem) GetInputVatRate() string`

GetInputVatRate returns the InputVatRate field if non-nil, zero value otherwise.

### GetInputVatRateOk

`func (o *InvoiceLineItem) GetInputVatRateOk() (*string, bool)`

GetInputVatRateOk returns a tuple with the InputVatRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputVatRate

`func (o *InvoiceLineItem) SetInputVatRate(v string)`

SetInputVatRate sets InputVatRate field to given value.

### HasInputVatRate

`func (o *InvoiceLineItem) HasInputVatRate() bool`

HasInputVatRate returns a boolean if a field has been set.

### SetInputVatRateNil

`func (o *InvoiceLineItem) SetInputVatRateNil(b bool)`

 SetInputVatRateNil sets the value for InputVatRate to be an explicit nil

### UnsetInputVatRate
`func (o *InvoiceLineItem) UnsetInputVatRate()`

UnsetInputVatRate ensures that no value is present for InputVatRate, not even an explicit nil
### GetIsIntraCommunityAcquisition

`func (o *InvoiceLineItem) GetIsIntraCommunityAcquisition() bool`

GetIsIntraCommunityAcquisition returns the IsIntraCommunityAcquisition field if non-nil, zero value otherwise.

### GetIsIntraCommunityAcquisitionOk

`func (o *InvoiceLineItem) GetIsIntraCommunityAcquisitionOk() (*bool, bool)`

GetIsIntraCommunityAcquisitionOk returns a tuple with the IsIntraCommunityAcquisition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsIntraCommunityAcquisition

`func (o *InvoiceLineItem) SetIsIntraCommunityAcquisition(v bool)`

SetIsIntraCommunityAcquisition sets IsIntraCommunityAcquisition field to given value.

### HasIsIntraCommunityAcquisition

`func (o *InvoiceLineItem) HasIsIntraCommunityAcquisition() bool`

HasIsIntraCommunityAcquisition returns a boolean if a field has been set.

### SetIsIntraCommunityAcquisitionNil

`func (o *InvoiceLineItem) SetIsIntraCommunityAcquisitionNil(b bool)`

 SetIsIntraCommunityAcquisitionNil sets the value for IsIntraCommunityAcquisition to be an explicit nil

### UnsetIsIntraCommunityAcquisition
`func (o *InvoiceLineItem) UnsetIsIntraCommunityAcquisition()`

UnsetIsIntraCommunityAcquisition ensures that no value is present for IsIntraCommunityAcquisition, not even an explicit nil
### GetIsMargin25a

`func (o *InvoiceLineItem) GetIsMargin25a() bool`

GetIsMargin25a returns the IsMargin25a field if non-nil, zero value otherwise.

### GetIsMargin25aOk

`func (o *InvoiceLineItem) GetIsMargin25aOk() (*bool, bool)`

GetIsMargin25aOk returns a tuple with the IsMargin25a field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMargin25a

`func (o *InvoiceLineItem) SetIsMargin25a(v bool)`

SetIsMargin25a sets IsMargin25a field to given value.

### HasIsMargin25a

`func (o *InvoiceLineItem) HasIsMargin25a() bool`

HasIsMargin25a returns a boolean if a field has been set.

### SetIsMargin25aNil

`func (o *InvoiceLineItem) SetIsMargin25aNil(b bool)`

 SetIsMargin25aNil sets the value for IsMargin25a to be an explicit nil

### UnsetIsMargin25a
`func (o *InvoiceLineItem) UnsetIsMargin25a()`

UnsetIsMargin25a ensures that no value is present for IsMargin25a, not even an explicit nil
### GetLedgerAccount

`func (o *InvoiceLineItem) GetLedgerAccount() string`

GetLedgerAccount returns the LedgerAccount field if non-nil, zero value otherwise.

### GetLedgerAccountOk

`func (o *InvoiceLineItem) GetLedgerAccountOk() (*string, bool)`

GetLedgerAccountOk returns a tuple with the LedgerAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLedgerAccount

`func (o *InvoiceLineItem) SetLedgerAccount(v string)`

SetLedgerAccount sets LedgerAccount field to given value.

### HasLedgerAccount

`func (o *InvoiceLineItem) HasLedgerAccount() bool`

HasLedgerAccount returns a boolean if a field has been set.

### SetLedgerAccountNil

`func (o *InvoiceLineItem) SetLedgerAccountNil(b bool)`

 SetLedgerAccountNil sets the value for LedgerAccount to be an explicit nil

### UnsetLedgerAccount
`func (o *InvoiceLineItem) UnsetLedgerAccount()`

UnsetLedgerAccount ensures that no value is present for LedgerAccount, not even an explicit nil
### GetLineTotal

`func (o *InvoiceLineItem) GetLineTotal() string`

GetLineTotal returns the LineTotal field if non-nil, zero value otherwise.

### GetLineTotalOk

`func (o *InvoiceLineItem) GetLineTotalOk() (*string, bool)`

GetLineTotalOk returns a tuple with the LineTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineTotal

`func (o *InvoiceLineItem) SetLineTotal(v string)`

SetLineTotal sets LineTotal field to given value.


### GetLineTotalGross

`func (o *InvoiceLineItem) GetLineTotalGross() string`

GetLineTotalGross returns the LineTotalGross field if non-nil, zero value otherwise.

### GetLineTotalGrossOk

`func (o *InvoiceLineItem) GetLineTotalGrossOk() (*string, bool)`

GetLineTotalGrossOk returns a tuple with the LineTotalGross field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineTotalGross

`func (o *InvoiceLineItem) SetLineTotalGross(v string)`

SetLineTotalGross sets LineTotalGross field to given value.

### HasLineTotalGross

`func (o *InvoiceLineItem) HasLineTotalGross() bool`

HasLineTotalGross returns a boolean if a field has been set.

### SetLineTotalGrossNil

`func (o *InvoiceLineItem) SetLineTotalGrossNil(b bool)`

 SetLineTotalGrossNil sets the value for LineTotalGross to be an explicit nil

### UnsetLineTotalGross
`func (o *InvoiceLineItem) UnsetLineTotalGross()`

UnsetLineTotalGross ensures that no value is present for LineTotalGross, not even an explicit nil
### GetMargin25aPurchasePrice

`func (o *InvoiceLineItem) GetMargin25aPurchasePrice() string`

GetMargin25aPurchasePrice returns the Margin25aPurchasePrice field if non-nil, zero value otherwise.

### GetMargin25aPurchasePriceOk

`func (o *InvoiceLineItem) GetMargin25aPurchasePriceOk() (*string, bool)`

GetMargin25aPurchasePriceOk returns a tuple with the Margin25aPurchasePrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMargin25aPurchasePrice

`func (o *InvoiceLineItem) SetMargin25aPurchasePrice(v string)`

SetMargin25aPurchasePrice sets Margin25aPurchasePrice field to given value.

### HasMargin25aPurchasePrice

`func (o *InvoiceLineItem) HasMargin25aPurchasePrice() bool`

HasMargin25aPurchasePrice returns a boolean if a field has been set.

### SetMargin25aPurchasePriceNil

`func (o *InvoiceLineItem) SetMargin25aPurchasePriceNil(b bool)`

 SetMargin25aPurchasePriceNil sets the value for Margin25aPurchasePrice to be an explicit nil

### UnsetMargin25aPurchasePrice
`func (o *InvoiceLineItem) UnsetMargin25aPurchasePrice()`

UnsetMargin25aPurchasePrice ensures that no value is present for Margin25aPurchasePrice, not even an explicit nil
### GetMeterPointId

`func (o *InvoiceLineItem) GetMeterPointId() string`

GetMeterPointId returns the MeterPointId field if non-nil, zero value otherwise.

### GetMeterPointIdOk

`func (o *InvoiceLineItem) GetMeterPointIdOk() (*string, bool)`

GetMeterPointIdOk returns a tuple with the MeterPointId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeterPointId

`func (o *InvoiceLineItem) SetMeterPointId(v string)`

SetMeterPointId sets MeterPointId field to given value.

### HasMeterPointId

`func (o *InvoiceLineItem) HasMeterPointId() bool`

HasMeterPointId returns a boolean if a field has been set.

### SetMeterPointIdNil

`func (o *InvoiceLineItem) SetMeterPointIdNil(b bool)`

 SetMeterPointIdNil sets the value for MeterPointId to be an explicit nil

### UnsetMeterPointId
`func (o *InvoiceLineItem) UnsetMeterPointId()`

UnsetMeterPointId ensures that no value is present for MeterPointId, not even an explicit nil
### GetPosition

`func (o *InvoiceLineItem) GetPosition() int64`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *InvoiceLineItem) GetPositionOk() (*int64, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *InvoiceLineItem) SetPosition(v int64)`

SetPosition sets Position field to given value.


### GetPriceComponents

`func (o *InvoiceLineItem) GetPriceComponents() interface{}`

GetPriceComponents returns the PriceComponents field if non-nil, zero value otherwise.

### GetPriceComponentsOk

`func (o *InvoiceLineItem) GetPriceComponentsOk() (*interface{}, bool)`

GetPriceComponentsOk returns a tuple with the PriceComponents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceComponents

`func (o *InvoiceLineItem) SetPriceComponents(v interface{})`

SetPriceComponents sets PriceComponents field to given value.

### HasPriceComponents

`func (o *InvoiceLineItem) HasPriceComponents() bool`

HasPriceComponents returns a boolean if a field has been set.

### SetPriceComponentsNil

`func (o *InvoiceLineItem) SetPriceComponentsNil(b bool)`

 SetPriceComponentsNil sets the value for PriceComponents to be an explicit nil

### UnsetPriceComponents
`func (o *InvoiceLineItem) UnsetPriceComponents()`

UnsetPriceComponents ensures that no value is present for PriceComponents, not even an explicit nil
### GetProductId

`func (o *InvoiceLineItem) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *InvoiceLineItem) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *InvoiceLineItem) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *InvoiceLineItem) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *InvoiceLineItem) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *InvoiceLineItem) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetProductSku

`func (o *InvoiceLineItem) GetProductSku() string`

GetProductSku returns the ProductSku field if non-nil, zero value otherwise.

### GetProductSkuOk

`func (o *InvoiceLineItem) GetProductSkuOk() (*string, bool)`

GetProductSkuOk returns a tuple with the ProductSku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductSku

`func (o *InvoiceLineItem) SetProductSku(v string)`

SetProductSku sets ProductSku field to given value.

### HasProductSku

`func (o *InvoiceLineItem) HasProductSku() bool`

HasProductSku returns a boolean if a field has been set.

### SetProductSkuNil

`func (o *InvoiceLineItem) SetProductSkuNil(b bool)`

 SetProductSkuNil sets the value for ProductSku to be an explicit nil

### UnsetProductSku
`func (o *InvoiceLineItem) UnsetProductSku()`

UnsetProductSku ensures that no value is present for ProductSku, not even an explicit nil
### GetQuantity

`func (o *InvoiceLineItem) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *InvoiceLineItem) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *InvoiceLineItem) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.


### GetSupplierArticleNumber

`func (o *InvoiceLineItem) GetSupplierArticleNumber() string`

GetSupplierArticleNumber returns the SupplierArticleNumber field if non-nil, zero value otherwise.

### GetSupplierArticleNumberOk

`func (o *InvoiceLineItem) GetSupplierArticleNumberOk() (*string, bool)`

GetSupplierArticleNumberOk returns a tuple with the SupplierArticleNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierArticleNumber

`func (o *InvoiceLineItem) SetSupplierArticleNumber(v string)`

SetSupplierArticleNumber sets SupplierArticleNumber field to given value.

### HasSupplierArticleNumber

`func (o *InvoiceLineItem) HasSupplierArticleNumber() bool`

HasSupplierArticleNumber returns a boolean if a field has been set.

### SetSupplierArticleNumberNil

`func (o *InvoiceLineItem) SetSupplierArticleNumberNil(b bool)`

 SetSupplierArticleNumberNil sets the value for SupplierArticleNumber to be an explicit nil

### UnsetSupplierArticleNumber
`func (o *InvoiceLineItem) UnsetSupplierArticleNumber()`

UnsetSupplierArticleNumber ensures that no value is present for SupplierArticleNumber, not even an explicit nil
### GetTaxRate

`func (o *InvoiceLineItem) GetTaxRate() string`

GetTaxRate returns the TaxRate field if non-nil, zero value otherwise.

### GetTaxRateOk

`func (o *InvoiceLineItem) GetTaxRateOk() (*string, bool)`

GetTaxRateOk returns a tuple with the TaxRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxRate

`func (o *InvoiceLineItem) SetTaxRate(v string)`

SetTaxRate sets TaxRate field to given value.

### HasTaxRate

`func (o *InvoiceLineItem) HasTaxRate() bool`

HasTaxRate returns a boolean if a field has been set.

### SetTaxRateNil

`func (o *InvoiceLineItem) SetTaxRateNil(b bool)`

 SetTaxRateNil sets the value for TaxRate to be an explicit nil

### UnsetTaxRate
`func (o *InvoiceLineItem) UnsetTaxRate()`

UnsetTaxRate ensures that no value is present for TaxRate, not even an explicit nil
### GetUnit

`func (o *InvoiceLineItem) GetUnit() interface{}`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *InvoiceLineItem) GetUnitOk() (*interface{}, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *InvoiceLineItem) SetUnit(v interface{})`

SetUnit sets Unit field to given value.


### SetUnitNil

`func (o *InvoiceLineItem) SetUnitNil(b bool)`

 SetUnitNil sets the value for Unit to be an explicit nil

### UnsetUnit
`func (o *InvoiceLineItem) UnsetUnit()`

UnsetUnit ensures that no value is present for Unit, not even an explicit nil
### GetUnitPrice

`func (o *InvoiceLineItem) GetUnitPrice() string`

GetUnitPrice returns the UnitPrice field if non-nil, zero value otherwise.

### GetUnitPriceOk

`func (o *InvoiceLineItem) GetUnitPriceOk() (*string, bool)`

GetUnitPriceOk returns a tuple with the UnitPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPrice

`func (o *InvoiceLineItem) SetUnitPrice(v string)`

SetUnitPrice sets UnitPrice field to given value.


### GetUsageDataId

`func (o *InvoiceLineItem) GetUsageDataId() string`

GetUsageDataId returns the UsageDataId field if non-nil, zero value otherwise.

### GetUsageDataIdOk

`func (o *InvoiceLineItem) GetUsageDataIdOk() (*string, bool)`

GetUsageDataIdOk returns a tuple with the UsageDataId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageDataId

`func (o *InvoiceLineItem) SetUsageDataId(v string)`

SetUsageDataId sets UsageDataId field to given value.

### HasUsageDataId

`func (o *InvoiceLineItem) HasUsageDataId() bool`

HasUsageDataId returns a boolean if a field has been set.

### SetUsageDataIdNil

`func (o *InvoiceLineItem) SetUsageDataIdNil(b bool)`

 SetUsageDataIdNil sets the value for UsageDataId to be an explicit nil

### UnsetUsageDataId
`func (o *InvoiceLineItem) UnsetUsageDataId()`

UnsetUsageDataId ensures that no value is present for UsageDataId, not even an explicit nil
### GetVatRateNominal

`func (o *InvoiceLineItem) GetVatRateNominal() string`

GetVatRateNominal returns the VatRateNominal field if non-nil, zero value otherwise.

### GetVatRateNominalOk

`func (o *InvoiceLineItem) GetVatRateNominalOk() (*string, bool)`

GetVatRateNominalOk returns a tuple with the VatRateNominal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatRateNominal

`func (o *InvoiceLineItem) SetVatRateNominal(v string)`

SetVatRateNominal sets VatRateNominal field to given value.

### HasVatRateNominal

`func (o *InvoiceLineItem) HasVatRateNominal() bool`

HasVatRateNominal returns a boolean if a field has been set.

### SetVatRateNominalNil

`func (o *InvoiceLineItem) SetVatRateNominalNil(b bool)`

 SetVatRateNominalNil sets the value for VatRateNominal to be an explicit nil

### UnsetVatRateNominal
`func (o *InvoiceLineItem) UnsetVatRateNominal()`

UnsetVatRateNominal ensures that no value is present for VatRateNominal, not even an explicit nil
### GetVatSpecialCase

`func (o *InvoiceLineItem) GetVatSpecialCase() string`

GetVatSpecialCase returns the VatSpecialCase field if non-nil, zero value otherwise.

### GetVatSpecialCaseOk

`func (o *InvoiceLineItem) GetVatSpecialCaseOk() (*string, bool)`

GetVatSpecialCaseOk returns a tuple with the VatSpecialCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatSpecialCase

`func (o *InvoiceLineItem) SetVatSpecialCase(v string)`

SetVatSpecialCase sets VatSpecialCase field to given value.

### HasVatSpecialCase

`func (o *InvoiceLineItem) HasVatSpecialCase() bool`

HasVatSpecialCase returns a boolean if a field has been set.

### SetVatSpecialCaseNil

`func (o *InvoiceLineItem) SetVatSpecialCaseNil(b bool)`

 SetVatSpecialCaseNil sets the value for VatSpecialCase to be an explicit nil

### UnsetVatSpecialCase
`func (o *InvoiceLineItem) UnsetVatSpecialCase()`

UnsetVatSpecialCase ensures that no value is present for VatSpecialCase, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


