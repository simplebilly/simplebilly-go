# ProductUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Availability** | Pointer to **NullableString** |  | [optional] 
**Barcode** | Pointer to **NullableString** |  | [optional] 
**Brand** | Pointer to **NullableString** |  | [optional] 
**CategoryId** | Pointer to **NullableString** |  | [optional] 
**Condition** | Pointer to **NullableString** |  | [optional] 
**DefaultLedgerAccount** | Pointer to **NullableString** |  | [optional] 
**DefaultPrice** | Pointer to **NullableString** |  | [optional] 
**DefaultPriceFormulaId** | Pointer to **NullableString** | References the price formula entity. | [optional] 
**DefaultTaxRate** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Gtin** | Pointer to **NullableString** |  | [optional] 
**Height** | Pointer to **NullableString** |  | [optional] 
**ImageLink** | Pointer to **NullableString** |  | [optional] 
**Images** | Pointer to **interface{}** |  | [optional] 
**IsTaxable** | Pointer to **NullableBool** |  | [optional] 
**Length** | Pointer to **NullableString** |  | [optional] 
**Link** | Pointer to **NullableString** |  | [optional] 
**MaxStock** | Pointer to **NullableInt64** | Target stock level used by reorder proposals. | [optional] 
**MinStock** | Pointer to **NullableInt64** | Reorder point — when stock falls below this, a reorder is suggested. | [optional] 
**Mpn** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**PackageHeight** | Pointer to **NullableString** |  | [optional] 
**PackageLength** | Pointer to **NullableString** |  | [optional] 
**PackageWeightUnit** | Pointer to **NullableString** |  | [optional] 
**PackageWeightValue** | Pointer to **NullableString** |  | [optional] 
**PackageWidth** | Pointer to **NullableString** |  | [optional] 
**ProductCode** | Pointer to **NullableString** |  | [optional] 
**ProductType** | Pointer to **NullableString** |  | [optional] 
**PurchasePrice** | Pointer to **NullableString** |  | [optional] 
**ReorderQuantity** | Pointer to **NullableInt64** | Suggested purchase quantity when a reorder proposal is created. | [optional] 
**SalePrice** | Pointer to **NullableString** |  | [optional] 
**ShippingPrice** | Pointer to **NullableString** |  | [optional] 
**ShippingRequiresInsurance** | Pointer to **NullableBool** |  | [optional] 
**Sku** | Pointer to **NullableString** |  | [optional] 
**StockQuantity** | Pointer to **NullableInt64** |  | [optional] 
**Tags** | Pointer to **interface{}** |  | [optional] 
**TaxPrice** | Pointer to **NullableString** |  | [optional] 
**TrackBatch** | Pointer to **NullableBool** | Whether this product requires batch (Chargennummer) tracking. | [optional] 
**TrackSerial** | Pointer to **NullableBool** | Whether this product requires serial-number tracking. | [optional] 
**Unit** | Pointer to **interface{}** |  | [optional] 
**WeightUnit** | Pointer to **NullableString** |  | [optional] 
**WeightValue** | Pointer to **NullableString** |  | [optional] 
**Width** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewProductUpdate

`func NewProductUpdate() *ProductUpdate`

NewProductUpdate instantiates a new ProductUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductUpdateWithDefaults

`func NewProductUpdateWithDefaults() *ProductUpdate`

NewProductUpdateWithDefaults instantiates a new ProductUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvailability

`func (o *ProductUpdate) GetAvailability() string`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *ProductUpdate) GetAvailabilityOk() (*string, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *ProductUpdate) SetAvailability(v string)`

SetAvailability sets Availability field to given value.

### HasAvailability

`func (o *ProductUpdate) HasAvailability() bool`

HasAvailability returns a boolean if a field has been set.

### SetAvailabilityNil

`func (o *ProductUpdate) SetAvailabilityNil(b bool)`

 SetAvailabilityNil sets the value for Availability to be an explicit nil

### UnsetAvailability
`func (o *ProductUpdate) UnsetAvailability()`

UnsetAvailability ensures that no value is present for Availability, not even an explicit nil
### GetBarcode

`func (o *ProductUpdate) GetBarcode() string`

GetBarcode returns the Barcode field if non-nil, zero value otherwise.

### GetBarcodeOk

`func (o *ProductUpdate) GetBarcodeOk() (*string, bool)`

GetBarcodeOk returns a tuple with the Barcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBarcode

`func (o *ProductUpdate) SetBarcode(v string)`

SetBarcode sets Barcode field to given value.

### HasBarcode

`func (o *ProductUpdate) HasBarcode() bool`

HasBarcode returns a boolean if a field has been set.

### SetBarcodeNil

`func (o *ProductUpdate) SetBarcodeNil(b bool)`

 SetBarcodeNil sets the value for Barcode to be an explicit nil

### UnsetBarcode
`func (o *ProductUpdate) UnsetBarcode()`

UnsetBarcode ensures that no value is present for Barcode, not even an explicit nil
### GetBrand

`func (o *ProductUpdate) GetBrand() string`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *ProductUpdate) GetBrandOk() (*string, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *ProductUpdate) SetBrand(v string)`

SetBrand sets Brand field to given value.

### HasBrand

`func (o *ProductUpdate) HasBrand() bool`

HasBrand returns a boolean if a field has been set.

### SetBrandNil

`func (o *ProductUpdate) SetBrandNil(b bool)`

 SetBrandNil sets the value for Brand to be an explicit nil

### UnsetBrand
`func (o *ProductUpdate) UnsetBrand()`

UnsetBrand ensures that no value is present for Brand, not even an explicit nil
### GetCategoryId

`func (o *ProductUpdate) GetCategoryId() string`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *ProductUpdate) GetCategoryIdOk() (*string, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *ProductUpdate) SetCategoryId(v string)`

SetCategoryId sets CategoryId field to given value.

### HasCategoryId

`func (o *ProductUpdate) HasCategoryId() bool`

HasCategoryId returns a boolean if a field has been set.

### SetCategoryIdNil

`func (o *ProductUpdate) SetCategoryIdNil(b bool)`

 SetCategoryIdNil sets the value for CategoryId to be an explicit nil

### UnsetCategoryId
`func (o *ProductUpdate) UnsetCategoryId()`

UnsetCategoryId ensures that no value is present for CategoryId, not even an explicit nil
### GetCondition

`func (o *ProductUpdate) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *ProductUpdate) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *ProductUpdate) SetCondition(v string)`

SetCondition sets Condition field to given value.

### HasCondition

`func (o *ProductUpdate) HasCondition() bool`

HasCondition returns a boolean if a field has been set.

### SetConditionNil

`func (o *ProductUpdate) SetConditionNil(b bool)`

 SetConditionNil sets the value for Condition to be an explicit nil

### UnsetCondition
`func (o *ProductUpdate) UnsetCondition()`

UnsetCondition ensures that no value is present for Condition, not even an explicit nil
### GetDefaultLedgerAccount

`func (o *ProductUpdate) GetDefaultLedgerAccount() string`

GetDefaultLedgerAccount returns the DefaultLedgerAccount field if non-nil, zero value otherwise.

### GetDefaultLedgerAccountOk

`func (o *ProductUpdate) GetDefaultLedgerAccountOk() (*string, bool)`

GetDefaultLedgerAccountOk returns a tuple with the DefaultLedgerAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultLedgerAccount

`func (o *ProductUpdate) SetDefaultLedgerAccount(v string)`

SetDefaultLedgerAccount sets DefaultLedgerAccount field to given value.

### HasDefaultLedgerAccount

`func (o *ProductUpdate) HasDefaultLedgerAccount() bool`

HasDefaultLedgerAccount returns a boolean if a field has been set.

### SetDefaultLedgerAccountNil

`func (o *ProductUpdate) SetDefaultLedgerAccountNil(b bool)`

 SetDefaultLedgerAccountNil sets the value for DefaultLedgerAccount to be an explicit nil

### UnsetDefaultLedgerAccount
`func (o *ProductUpdate) UnsetDefaultLedgerAccount()`

UnsetDefaultLedgerAccount ensures that no value is present for DefaultLedgerAccount, not even an explicit nil
### GetDefaultPrice

`func (o *ProductUpdate) GetDefaultPrice() string`

GetDefaultPrice returns the DefaultPrice field if non-nil, zero value otherwise.

### GetDefaultPriceOk

`func (o *ProductUpdate) GetDefaultPriceOk() (*string, bool)`

GetDefaultPriceOk returns a tuple with the DefaultPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultPrice

`func (o *ProductUpdate) SetDefaultPrice(v string)`

SetDefaultPrice sets DefaultPrice field to given value.

### HasDefaultPrice

`func (o *ProductUpdate) HasDefaultPrice() bool`

HasDefaultPrice returns a boolean if a field has been set.

### SetDefaultPriceNil

`func (o *ProductUpdate) SetDefaultPriceNil(b bool)`

 SetDefaultPriceNil sets the value for DefaultPrice to be an explicit nil

### UnsetDefaultPrice
`func (o *ProductUpdate) UnsetDefaultPrice()`

UnsetDefaultPrice ensures that no value is present for DefaultPrice, not even an explicit nil
### GetDefaultPriceFormulaId

`func (o *ProductUpdate) GetDefaultPriceFormulaId() string`

GetDefaultPriceFormulaId returns the DefaultPriceFormulaId field if non-nil, zero value otherwise.

### GetDefaultPriceFormulaIdOk

`func (o *ProductUpdate) GetDefaultPriceFormulaIdOk() (*string, bool)`

GetDefaultPriceFormulaIdOk returns a tuple with the DefaultPriceFormulaId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultPriceFormulaId

`func (o *ProductUpdate) SetDefaultPriceFormulaId(v string)`

SetDefaultPriceFormulaId sets DefaultPriceFormulaId field to given value.

### HasDefaultPriceFormulaId

`func (o *ProductUpdate) HasDefaultPriceFormulaId() bool`

HasDefaultPriceFormulaId returns a boolean if a field has been set.

### SetDefaultPriceFormulaIdNil

`func (o *ProductUpdate) SetDefaultPriceFormulaIdNil(b bool)`

 SetDefaultPriceFormulaIdNil sets the value for DefaultPriceFormulaId to be an explicit nil

### UnsetDefaultPriceFormulaId
`func (o *ProductUpdate) UnsetDefaultPriceFormulaId()`

UnsetDefaultPriceFormulaId ensures that no value is present for DefaultPriceFormulaId, not even an explicit nil
### GetDefaultTaxRate

`func (o *ProductUpdate) GetDefaultTaxRate() string`

GetDefaultTaxRate returns the DefaultTaxRate field if non-nil, zero value otherwise.

### GetDefaultTaxRateOk

`func (o *ProductUpdate) GetDefaultTaxRateOk() (*string, bool)`

GetDefaultTaxRateOk returns a tuple with the DefaultTaxRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultTaxRate

`func (o *ProductUpdate) SetDefaultTaxRate(v string)`

SetDefaultTaxRate sets DefaultTaxRate field to given value.

### HasDefaultTaxRate

`func (o *ProductUpdate) HasDefaultTaxRate() bool`

HasDefaultTaxRate returns a boolean if a field has been set.

### SetDefaultTaxRateNil

`func (o *ProductUpdate) SetDefaultTaxRateNil(b bool)`

 SetDefaultTaxRateNil sets the value for DefaultTaxRate to be an explicit nil

### UnsetDefaultTaxRate
`func (o *ProductUpdate) UnsetDefaultTaxRate()`

UnsetDefaultTaxRate ensures that no value is present for DefaultTaxRate, not even an explicit nil
### GetDescription

`func (o *ProductUpdate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProductUpdate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProductUpdate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProductUpdate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ProductUpdate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ProductUpdate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetGtin

`func (o *ProductUpdate) GetGtin() string`

GetGtin returns the Gtin field if non-nil, zero value otherwise.

### GetGtinOk

`func (o *ProductUpdate) GetGtinOk() (*string, bool)`

GetGtinOk returns a tuple with the Gtin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGtin

`func (o *ProductUpdate) SetGtin(v string)`

SetGtin sets Gtin field to given value.

### HasGtin

`func (o *ProductUpdate) HasGtin() bool`

HasGtin returns a boolean if a field has been set.

### SetGtinNil

`func (o *ProductUpdate) SetGtinNil(b bool)`

 SetGtinNil sets the value for Gtin to be an explicit nil

### UnsetGtin
`func (o *ProductUpdate) UnsetGtin()`

UnsetGtin ensures that no value is present for Gtin, not even an explicit nil
### GetHeight

`func (o *ProductUpdate) GetHeight() string`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *ProductUpdate) GetHeightOk() (*string, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *ProductUpdate) SetHeight(v string)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *ProductUpdate) HasHeight() bool`

HasHeight returns a boolean if a field has been set.

### SetHeightNil

`func (o *ProductUpdate) SetHeightNil(b bool)`

 SetHeightNil sets the value for Height to be an explicit nil

### UnsetHeight
`func (o *ProductUpdate) UnsetHeight()`

UnsetHeight ensures that no value is present for Height, not even an explicit nil
### GetImageLink

`func (o *ProductUpdate) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *ProductUpdate) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *ProductUpdate) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *ProductUpdate) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### SetImageLinkNil

`func (o *ProductUpdate) SetImageLinkNil(b bool)`

 SetImageLinkNil sets the value for ImageLink to be an explicit nil

### UnsetImageLink
`func (o *ProductUpdate) UnsetImageLink()`

UnsetImageLink ensures that no value is present for ImageLink, not even an explicit nil
### GetImages

`func (o *ProductUpdate) GetImages() interface{}`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *ProductUpdate) GetImagesOk() (*interface{}, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *ProductUpdate) SetImages(v interface{})`

SetImages sets Images field to given value.

### HasImages

`func (o *ProductUpdate) HasImages() bool`

HasImages returns a boolean if a field has been set.

### SetImagesNil

`func (o *ProductUpdate) SetImagesNil(b bool)`

 SetImagesNil sets the value for Images to be an explicit nil

### UnsetImages
`func (o *ProductUpdate) UnsetImages()`

UnsetImages ensures that no value is present for Images, not even an explicit nil
### GetIsTaxable

`func (o *ProductUpdate) GetIsTaxable() bool`

GetIsTaxable returns the IsTaxable field if non-nil, zero value otherwise.

### GetIsTaxableOk

`func (o *ProductUpdate) GetIsTaxableOk() (*bool, bool)`

GetIsTaxableOk returns a tuple with the IsTaxable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTaxable

`func (o *ProductUpdate) SetIsTaxable(v bool)`

SetIsTaxable sets IsTaxable field to given value.

### HasIsTaxable

`func (o *ProductUpdate) HasIsTaxable() bool`

HasIsTaxable returns a boolean if a field has been set.

### SetIsTaxableNil

`func (o *ProductUpdate) SetIsTaxableNil(b bool)`

 SetIsTaxableNil sets the value for IsTaxable to be an explicit nil

### UnsetIsTaxable
`func (o *ProductUpdate) UnsetIsTaxable()`

UnsetIsTaxable ensures that no value is present for IsTaxable, not even an explicit nil
### GetLength

`func (o *ProductUpdate) GetLength() string`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *ProductUpdate) GetLengthOk() (*string, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *ProductUpdate) SetLength(v string)`

SetLength sets Length field to given value.

### HasLength

`func (o *ProductUpdate) HasLength() bool`

HasLength returns a boolean if a field has been set.

### SetLengthNil

`func (o *ProductUpdate) SetLengthNil(b bool)`

 SetLengthNil sets the value for Length to be an explicit nil

### UnsetLength
`func (o *ProductUpdate) UnsetLength()`

UnsetLength ensures that no value is present for Length, not even an explicit nil
### GetLink

`func (o *ProductUpdate) GetLink() string`

GetLink returns the Link field if non-nil, zero value otherwise.

### GetLinkOk

`func (o *ProductUpdate) GetLinkOk() (*string, bool)`

GetLinkOk returns a tuple with the Link field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLink

`func (o *ProductUpdate) SetLink(v string)`

SetLink sets Link field to given value.

### HasLink

`func (o *ProductUpdate) HasLink() bool`

HasLink returns a boolean if a field has been set.

### SetLinkNil

`func (o *ProductUpdate) SetLinkNil(b bool)`

 SetLinkNil sets the value for Link to be an explicit nil

### UnsetLink
`func (o *ProductUpdate) UnsetLink()`

UnsetLink ensures that no value is present for Link, not even an explicit nil
### GetMaxStock

`func (o *ProductUpdate) GetMaxStock() int64`

GetMaxStock returns the MaxStock field if non-nil, zero value otherwise.

### GetMaxStockOk

`func (o *ProductUpdate) GetMaxStockOk() (*int64, bool)`

GetMaxStockOk returns a tuple with the MaxStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxStock

`func (o *ProductUpdate) SetMaxStock(v int64)`

SetMaxStock sets MaxStock field to given value.

### HasMaxStock

`func (o *ProductUpdate) HasMaxStock() bool`

HasMaxStock returns a boolean if a field has been set.

### SetMaxStockNil

`func (o *ProductUpdate) SetMaxStockNil(b bool)`

 SetMaxStockNil sets the value for MaxStock to be an explicit nil

### UnsetMaxStock
`func (o *ProductUpdate) UnsetMaxStock()`

UnsetMaxStock ensures that no value is present for MaxStock, not even an explicit nil
### GetMinStock

`func (o *ProductUpdate) GetMinStock() int64`

GetMinStock returns the MinStock field if non-nil, zero value otherwise.

### GetMinStockOk

`func (o *ProductUpdate) GetMinStockOk() (*int64, bool)`

GetMinStockOk returns a tuple with the MinStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinStock

`func (o *ProductUpdate) SetMinStock(v int64)`

SetMinStock sets MinStock field to given value.

### HasMinStock

`func (o *ProductUpdate) HasMinStock() bool`

HasMinStock returns a boolean if a field has been set.

### SetMinStockNil

`func (o *ProductUpdate) SetMinStockNil(b bool)`

 SetMinStockNil sets the value for MinStock to be an explicit nil

### UnsetMinStock
`func (o *ProductUpdate) UnsetMinStock()`

UnsetMinStock ensures that no value is present for MinStock, not even an explicit nil
### GetMpn

`func (o *ProductUpdate) GetMpn() string`

GetMpn returns the Mpn field if non-nil, zero value otherwise.

### GetMpnOk

`func (o *ProductUpdate) GetMpnOk() (*string, bool)`

GetMpnOk returns a tuple with the Mpn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMpn

`func (o *ProductUpdate) SetMpn(v string)`

SetMpn sets Mpn field to given value.

### HasMpn

`func (o *ProductUpdate) HasMpn() bool`

HasMpn returns a boolean if a field has been set.

### SetMpnNil

`func (o *ProductUpdate) SetMpnNil(b bool)`

 SetMpnNil sets the value for Mpn to be an explicit nil

### UnsetMpn
`func (o *ProductUpdate) UnsetMpn()`

UnsetMpn ensures that no value is present for Mpn, not even an explicit nil
### GetName

`func (o *ProductUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ProductUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ProductUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetPackageHeight

`func (o *ProductUpdate) GetPackageHeight() string`

GetPackageHeight returns the PackageHeight field if non-nil, zero value otherwise.

### GetPackageHeightOk

`func (o *ProductUpdate) GetPackageHeightOk() (*string, bool)`

GetPackageHeightOk returns a tuple with the PackageHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageHeight

`func (o *ProductUpdate) SetPackageHeight(v string)`

SetPackageHeight sets PackageHeight field to given value.

### HasPackageHeight

`func (o *ProductUpdate) HasPackageHeight() bool`

HasPackageHeight returns a boolean if a field has been set.

### SetPackageHeightNil

`func (o *ProductUpdate) SetPackageHeightNil(b bool)`

 SetPackageHeightNil sets the value for PackageHeight to be an explicit nil

### UnsetPackageHeight
`func (o *ProductUpdate) UnsetPackageHeight()`

UnsetPackageHeight ensures that no value is present for PackageHeight, not even an explicit nil
### GetPackageLength

`func (o *ProductUpdate) GetPackageLength() string`

GetPackageLength returns the PackageLength field if non-nil, zero value otherwise.

### GetPackageLengthOk

`func (o *ProductUpdate) GetPackageLengthOk() (*string, bool)`

GetPackageLengthOk returns a tuple with the PackageLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageLength

`func (o *ProductUpdate) SetPackageLength(v string)`

SetPackageLength sets PackageLength field to given value.

### HasPackageLength

`func (o *ProductUpdate) HasPackageLength() bool`

HasPackageLength returns a boolean if a field has been set.

### SetPackageLengthNil

`func (o *ProductUpdate) SetPackageLengthNil(b bool)`

 SetPackageLengthNil sets the value for PackageLength to be an explicit nil

### UnsetPackageLength
`func (o *ProductUpdate) UnsetPackageLength()`

UnsetPackageLength ensures that no value is present for PackageLength, not even an explicit nil
### GetPackageWeightUnit

`func (o *ProductUpdate) GetPackageWeightUnit() string`

GetPackageWeightUnit returns the PackageWeightUnit field if non-nil, zero value otherwise.

### GetPackageWeightUnitOk

`func (o *ProductUpdate) GetPackageWeightUnitOk() (*string, bool)`

GetPackageWeightUnitOk returns a tuple with the PackageWeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageWeightUnit

`func (o *ProductUpdate) SetPackageWeightUnit(v string)`

SetPackageWeightUnit sets PackageWeightUnit field to given value.

### HasPackageWeightUnit

`func (o *ProductUpdate) HasPackageWeightUnit() bool`

HasPackageWeightUnit returns a boolean if a field has been set.

### SetPackageWeightUnitNil

`func (o *ProductUpdate) SetPackageWeightUnitNil(b bool)`

 SetPackageWeightUnitNil sets the value for PackageWeightUnit to be an explicit nil

### UnsetPackageWeightUnit
`func (o *ProductUpdate) UnsetPackageWeightUnit()`

UnsetPackageWeightUnit ensures that no value is present for PackageWeightUnit, not even an explicit nil
### GetPackageWeightValue

`func (o *ProductUpdate) GetPackageWeightValue() string`

GetPackageWeightValue returns the PackageWeightValue field if non-nil, zero value otherwise.

### GetPackageWeightValueOk

`func (o *ProductUpdate) GetPackageWeightValueOk() (*string, bool)`

GetPackageWeightValueOk returns a tuple with the PackageWeightValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageWeightValue

`func (o *ProductUpdate) SetPackageWeightValue(v string)`

SetPackageWeightValue sets PackageWeightValue field to given value.

### HasPackageWeightValue

`func (o *ProductUpdate) HasPackageWeightValue() bool`

HasPackageWeightValue returns a boolean if a field has been set.

### SetPackageWeightValueNil

`func (o *ProductUpdate) SetPackageWeightValueNil(b bool)`

 SetPackageWeightValueNil sets the value for PackageWeightValue to be an explicit nil

### UnsetPackageWeightValue
`func (o *ProductUpdate) UnsetPackageWeightValue()`

UnsetPackageWeightValue ensures that no value is present for PackageWeightValue, not even an explicit nil
### GetPackageWidth

`func (o *ProductUpdate) GetPackageWidth() string`

GetPackageWidth returns the PackageWidth field if non-nil, zero value otherwise.

### GetPackageWidthOk

`func (o *ProductUpdate) GetPackageWidthOk() (*string, bool)`

GetPackageWidthOk returns a tuple with the PackageWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageWidth

`func (o *ProductUpdate) SetPackageWidth(v string)`

SetPackageWidth sets PackageWidth field to given value.

### HasPackageWidth

`func (o *ProductUpdate) HasPackageWidth() bool`

HasPackageWidth returns a boolean if a field has been set.

### SetPackageWidthNil

`func (o *ProductUpdate) SetPackageWidthNil(b bool)`

 SetPackageWidthNil sets the value for PackageWidth to be an explicit nil

### UnsetPackageWidth
`func (o *ProductUpdate) UnsetPackageWidth()`

UnsetPackageWidth ensures that no value is present for PackageWidth, not even an explicit nil
### GetProductCode

`func (o *ProductUpdate) GetProductCode() string`

GetProductCode returns the ProductCode field if non-nil, zero value otherwise.

### GetProductCodeOk

`func (o *ProductUpdate) GetProductCodeOk() (*string, bool)`

GetProductCodeOk returns a tuple with the ProductCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductCode

`func (o *ProductUpdate) SetProductCode(v string)`

SetProductCode sets ProductCode field to given value.

### HasProductCode

`func (o *ProductUpdate) HasProductCode() bool`

HasProductCode returns a boolean if a field has been set.

### SetProductCodeNil

`func (o *ProductUpdate) SetProductCodeNil(b bool)`

 SetProductCodeNil sets the value for ProductCode to be an explicit nil

### UnsetProductCode
`func (o *ProductUpdate) UnsetProductCode()`

UnsetProductCode ensures that no value is present for ProductCode, not even an explicit nil
### GetProductType

`func (o *ProductUpdate) GetProductType() string`

GetProductType returns the ProductType field if non-nil, zero value otherwise.

### GetProductTypeOk

`func (o *ProductUpdate) GetProductTypeOk() (*string, bool)`

GetProductTypeOk returns a tuple with the ProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductType

`func (o *ProductUpdate) SetProductType(v string)`

SetProductType sets ProductType field to given value.

### HasProductType

`func (o *ProductUpdate) HasProductType() bool`

HasProductType returns a boolean if a field has been set.

### SetProductTypeNil

`func (o *ProductUpdate) SetProductTypeNil(b bool)`

 SetProductTypeNil sets the value for ProductType to be an explicit nil

### UnsetProductType
`func (o *ProductUpdate) UnsetProductType()`

UnsetProductType ensures that no value is present for ProductType, not even an explicit nil
### GetPurchasePrice

`func (o *ProductUpdate) GetPurchasePrice() string`

GetPurchasePrice returns the PurchasePrice field if non-nil, zero value otherwise.

### GetPurchasePriceOk

`func (o *ProductUpdate) GetPurchasePriceOk() (*string, bool)`

GetPurchasePriceOk returns a tuple with the PurchasePrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchasePrice

`func (o *ProductUpdate) SetPurchasePrice(v string)`

SetPurchasePrice sets PurchasePrice field to given value.

### HasPurchasePrice

`func (o *ProductUpdate) HasPurchasePrice() bool`

HasPurchasePrice returns a boolean if a field has been set.

### SetPurchasePriceNil

`func (o *ProductUpdate) SetPurchasePriceNil(b bool)`

 SetPurchasePriceNil sets the value for PurchasePrice to be an explicit nil

### UnsetPurchasePrice
`func (o *ProductUpdate) UnsetPurchasePrice()`

UnsetPurchasePrice ensures that no value is present for PurchasePrice, not even an explicit nil
### GetReorderQuantity

`func (o *ProductUpdate) GetReorderQuantity() int64`

GetReorderQuantity returns the ReorderQuantity field if non-nil, zero value otherwise.

### GetReorderQuantityOk

`func (o *ProductUpdate) GetReorderQuantityOk() (*int64, bool)`

GetReorderQuantityOk returns a tuple with the ReorderQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReorderQuantity

`func (o *ProductUpdate) SetReorderQuantity(v int64)`

SetReorderQuantity sets ReorderQuantity field to given value.

### HasReorderQuantity

`func (o *ProductUpdate) HasReorderQuantity() bool`

HasReorderQuantity returns a boolean if a field has been set.

### SetReorderQuantityNil

`func (o *ProductUpdate) SetReorderQuantityNil(b bool)`

 SetReorderQuantityNil sets the value for ReorderQuantity to be an explicit nil

### UnsetReorderQuantity
`func (o *ProductUpdate) UnsetReorderQuantity()`

UnsetReorderQuantity ensures that no value is present for ReorderQuantity, not even an explicit nil
### GetSalePrice

`func (o *ProductUpdate) GetSalePrice() string`

GetSalePrice returns the SalePrice field if non-nil, zero value otherwise.

### GetSalePriceOk

`func (o *ProductUpdate) GetSalePriceOk() (*string, bool)`

GetSalePriceOk returns a tuple with the SalePrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalePrice

`func (o *ProductUpdate) SetSalePrice(v string)`

SetSalePrice sets SalePrice field to given value.

### HasSalePrice

`func (o *ProductUpdate) HasSalePrice() bool`

HasSalePrice returns a boolean if a field has been set.

### SetSalePriceNil

`func (o *ProductUpdate) SetSalePriceNil(b bool)`

 SetSalePriceNil sets the value for SalePrice to be an explicit nil

### UnsetSalePrice
`func (o *ProductUpdate) UnsetSalePrice()`

UnsetSalePrice ensures that no value is present for SalePrice, not even an explicit nil
### GetShippingPrice

`func (o *ProductUpdate) GetShippingPrice() string`

GetShippingPrice returns the ShippingPrice field if non-nil, zero value otherwise.

### GetShippingPriceOk

`func (o *ProductUpdate) GetShippingPriceOk() (*string, bool)`

GetShippingPriceOk returns a tuple with the ShippingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingPrice

`func (o *ProductUpdate) SetShippingPrice(v string)`

SetShippingPrice sets ShippingPrice field to given value.

### HasShippingPrice

`func (o *ProductUpdate) HasShippingPrice() bool`

HasShippingPrice returns a boolean if a field has been set.

### SetShippingPriceNil

`func (o *ProductUpdate) SetShippingPriceNil(b bool)`

 SetShippingPriceNil sets the value for ShippingPrice to be an explicit nil

### UnsetShippingPrice
`func (o *ProductUpdate) UnsetShippingPrice()`

UnsetShippingPrice ensures that no value is present for ShippingPrice, not even an explicit nil
### GetShippingRequiresInsurance

`func (o *ProductUpdate) GetShippingRequiresInsurance() bool`

GetShippingRequiresInsurance returns the ShippingRequiresInsurance field if non-nil, zero value otherwise.

### GetShippingRequiresInsuranceOk

`func (o *ProductUpdate) GetShippingRequiresInsuranceOk() (*bool, bool)`

GetShippingRequiresInsuranceOk returns a tuple with the ShippingRequiresInsurance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRequiresInsurance

`func (o *ProductUpdate) SetShippingRequiresInsurance(v bool)`

SetShippingRequiresInsurance sets ShippingRequiresInsurance field to given value.

### HasShippingRequiresInsurance

`func (o *ProductUpdate) HasShippingRequiresInsurance() bool`

HasShippingRequiresInsurance returns a boolean if a field has been set.

### SetShippingRequiresInsuranceNil

`func (o *ProductUpdate) SetShippingRequiresInsuranceNil(b bool)`

 SetShippingRequiresInsuranceNil sets the value for ShippingRequiresInsurance to be an explicit nil

### UnsetShippingRequiresInsurance
`func (o *ProductUpdate) UnsetShippingRequiresInsurance()`

UnsetShippingRequiresInsurance ensures that no value is present for ShippingRequiresInsurance, not even an explicit nil
### GetSku

`func (o *ProductUpdate) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *ProductUpdate) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *ProductUpdate) SetSku(v string)`

SetSku sets Sku field to given value.

### HasSku

`func (o *ProductUpdate) HasSku() bool`

HasSku returns a boolean if a field has been set.

### SetSkuNil

`func (o *ProductUpdate) SetSkuNil(b bool)`

 SetSkuNil sets the value for Sku to be an explicit nil

### UnsetSku
`func (o *ProductUpdate) UnsetSku()`

UnsetSku ensures that no value is present for Sku, not even an explicit nil
### GetStockQuantity

`func (o *ProductUpdate) GetStockQuantity() int64`

GetStockQuantity returns the StockQuantity field if non-nil, zero value otherwise.

### GetStockQuantityOk

`func (o *ProductUpdate) GetStockQuantityOk() (*int64, bool)`

GetStockQuantityOk returns a tuple with the StockQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStockQuantity

`func (o *ProductUpdate) SetStockQuantity(v int64)`

SetStockQuantity sets StockQuantity field to given value.

### HasStockQuantity

`func (o *ProductUpdate) HasStockQuantity() bool`

HasStockQuantity returns a boolean if a field has been set.

### SetStockQuantityNil

`func (o *ProductUpdate) SetStockQuantityNil(b bool)`

 SetStockQuantityNil sets the value for StockQuantity to be an explicit nil

### UnsetStockQuantity
`func (o *ProductUpdate) UnsetStockQuantity()`

UnsetStockQuantity ensures that no value is present for StockQuantity, not even an explicit nil
### GetTags

`func (o *ProductUpdate) GetTags() interface{}`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ProductUpdate) GetTagsOk() (*interface{}, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ProductUpdate) SetTags(v interface{})`

SetTags sets Tags field to given value.

### HasTags

`func (o *ProductUpdate) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *ProductUpdate) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *ProductUpdate) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTaxPrice

`func (o *ProductUpdate) GetTaxPrice() string`

GetTaxPrice returns the TaxPrice field if non-nil, zero value otherwise.

### GetTaxPriceOk

`func (o *ProductUpdate) GetTaxPriceOk() (*string, bool)`

GetTaxPriceOk returns a tuple with the TaxPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxPrice

`func (o *ProductUpdate) SetTaxPrice(v string)`

SetTaxPrice sets TaxPrice field to given value.

### HasTaxPrice

`func (o *ProductUpdate) HasTaxPrice() bool`

HasTaxPrice returns a boolean if a field has been set.

### SetTaxPriceNil

`func (o *ProductUpdate) SetTaxPriceNil(b bool)`

 SetTaxPriceNil sets the value for TaxPrice to be an explicit nil

### UnsetTaxPrice
`func (o *ProductUpdate) UnsetTaxPrice()`

UnsetTaxPrice ensures that no value is present for TaxPrice, not even an explicit nil
### GetTrackBatch

`func (o *ProductUpdate) GetTrackBatch() bool`

GetTrackBatch returns the TrackBatch field if non-nil, zero value otherwise.

### GetTrackBatchOk

`func (o *ProductUpdate) GetTrackBatchOk() (*bool, bool)`

GetTrackBatchOk returns a tuple with the TrackBatch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackBatch

`func (o *ProductUpdate) SetTrackBatch(v bool)`

SetTrackBatch sets TrackBatch field to given value.

### HasTrackBatch

`func (o *ProductUpdate) HasTrackBatch() bool`

HasTrackBatch returns a boolean if a field has been set.

### SetTrackBatchNil

`func (o *ProductUpdate) SetTrackBatchNil(b bool)`

 SetTrackBatchNil sets the value for TrackBatch to be an explicit nil

### UnsetTrackBatch
`func (o *ProductUpdate) UnsetTrackBatch()`

UnsetTrackBatch ensures that no value is present for TrackBatch, not even an explicit nil
### GetTrackSerial

`func (o *ProductUpdate) GetTrackSerial() bool`

GetTrackSerial returns the TrackSerial field if non-nil, zero value otherwise.

### GetTrackSerialOk

`func (o *ProductUpdate) GetTrackSerialOk() (*bool, bool)`

GetTrackSerialOk returns a tuple with the TrackSerial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackSerial

`func (o *ProductUpdate) SetTrackSerial(v bool)`

SetTrackSerial sets TrackSerial field to given value.

### HasTrackSerial

`func (o *ProductUpdate) HasTrackSerial() bool`

HasTrackSerial returns a boolean if a field has been set.

### SetTrackSerialNil

`func (o *ProductUpdate) SetTrackSerialNil(b bool)`

 SetTrackSerialNil sets the value for TrackSerial to be an explicit nil

### UnsetTrackSerial
`func (o *ProductUpdate) UnsetTrackSerial()`

UnsetTrackSerial ensures that no value is present for TrackSerial, not even an explicit nil
### GetUnit

`func (o *ProductUpdate) GetUnit() interface{}`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *ProductUpdate) GetUnitOk() (*interface{}, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *ProductUpdate) SetUnit(v interface{})`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *ProductUpdate) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### SetUnitNil

`func (o *ProductUpdate) SetUnitNil(b bool)`

 SetUnitNil sets the value for Unit to be an explicit nil

### UnsetUnit
`func (o *ProductUpdate) UnsetUnit()`

UnsetUnit ensures that no value is present for Unit, not even an explicit nil
### GetWeightUnit

`func (o *ProductUpdate) GetWeightUnit() string`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *ProductUpdate) GetWeightUnitOk() (*string, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *ProductUpdate) SetWeightUnit(v string)`

SetWeightUnit sets WeightUnit field to given value.

### HasWeightUnit

`func (o *ProductUpdate) HasWeightUnit() bool`

HasWeightUnit returns a boolean if a field has been set.

### SetWeightUnitNil

`func (o *ProductUpdate) SetWeightUnitNil(b bool)`

 SetWeightUnitNil sets the value for WeightUnit to be an explicit nil

### UnsetWeightUnit
`func (o *ProductUpdate) UnsetWeightUnit()`

UnsetWeightUnit ensures that no value is present for WeightUnit, not even an explicit nil
### GetWeightValue

`func (o *ProductUpdate) GetWeightValue() string`

GetWeightValue returns the WeightValue field if non-nil, zero value otherwise.

### GetWeightValueOk

`func (o *ProductUpdate) GetWeightValueOk() (*string, bool)`

GetWeightValueOk returns a tuple with the WeightValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightValue

`func (o *ProductUpdate) SetWeightValue(v string)`

SetWeightValue sets WeightValue field to given value.

### HasWeightValue

`func (o *ProductUpdate) HasWeightValue() bool`

HasWeightValue returns a boolean if a field has been set.

### SetWeightValueNil

`func (o *ProductUpdate) SetWeightValueNil(b bool)`

 SetWeightValueNil sets the value for WeightValue to be an explicit nil

### UnsetWeightValue
`func (o *ProductUpdate) UnsetWeightValue()`

UnsetWeightValue ensures that no value is present for WeightValue, not even an explicit nil
### GetWidth

`func (o *ProductUpdate) GetWidth() string`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *ProductUpdate) GetWidthOk() (*string, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *ProductUpdate) SetWidth(v string)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *ProductUpdate) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### SetWidthNil

`func (o *ProductUpdate) SetWidthNil(b bool)`

 SetWidthNil sets the value for Width to be an explicit nil

### UnsetWidth
`func (o *ProductUpdate) UnsetWidth()`

UnsetWidth ensures that no value is present for Width, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


