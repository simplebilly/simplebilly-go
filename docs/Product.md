# Product

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
**IsTaxable** | Pointer to **bool** |  | [optional] 
**Length** | Pointer to **NullableString** |  | [optional] 
**Link** | Pointer to **NullableString** |  | [optional] 
**MaxStock** | Pointer to **NullableInt64** | Target stock level used by reorder proposals. | [optional] 
**MinStock** | Pointer to **NullableInt64** | Reorder point — when stock falls below this, a reorder is suggested. | [optional] 
**Mpn** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**PackageHeight** | Pointer to **NullableString** |  | [optional] 
**PackageLength** | Pointer to **NullableString** |  | [optional] 
**PackageWeightUnit** | Pointer to **NullableString** |  | [optional] 
**PackageWeightValue** | Pointer to **NullableString** |  | [optional] 
**PackageWidth** | Pointer to **NullableString** |  | [optional] 
**ProductCode** | **string** |  | 
**ProductType** | Pointer to **NullableString** |  | [optional] 
**PurchasePrice** | Pointer to **NullableString** |  | [optional] 
**ReorderQuantity** | Pointer to **NullableInt64** | Suggested purchase quantity when a reorder proposal is created. | [optional] 
**SalePrice** | Pointer to **NullableString** |  | [optional] 
**ShippingPrice** | Pointer to **NullableString** |  | [optional] 
**ShippingRequiresInsurance** | Pointer to **NullableBool** |  | [optional] 
**Sku** | **string** |  | 
**StockQuantity** | Pointer to **NullableInt64** |  | [optional] 
**Tags** | Pointer to **interface{}** |  | [optional] 
**TaxPrice** | Pointer to **NullableString** |  | [optional] 
**TrackBatch** | Pointer to **bool** | Whether this product requires batch (Chargennummer) tracking. | [optional] 
**TrackSerial** | Pointer to **bool** | Whether this product requires serial-number tracking. | [optional] 
**Unit** | Pointer to **interface{}** |  | [optional] 
**WeightUnit** | Pointer to **NullableString** |  | [optional] 
**WeightValue** | Pointer to **NullableString** |  | [optional] 
**Width** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewProduct

`func NewProduct(name string, productCode string, sku string, ) *Product`

NewProduct instantiates a new Product object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductWithDefaults

`func NewProductWithDefaults() *Product`

NewProductWithDefaults instantiates a new Product object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvailability

`func (o *Product) GetAvailability() string`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *Product) GetAvailabilityOk() (*string, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *Product) SetAvailability(v string)`

SetAvailability sets Availability field to given value.

### HasAvailability

`func (o *Product) HasAvailability() bool`

HasAvailability returns a boolean if a field has been set.

### SetAvailabilityNil

`func (o *Product) SetAvailabilityNil(b bool)`

 SetAvailabilityNil sets the value for Availability to be an explicit nil

### UnsetAvailability
`func (o *Product) UnsetAvailability()`

UnsetAvailability ensures that no value is present for Availability, not even an explicit nil
### GetBarcode

`func (o *Product) GetBarcode() string`

GetBarcode returns the Barcode field if non-nil, zero value otherwise.

### GetBarcodeOk

`func (o *Product) GetBarcodeOk() (*string, bool)`

GetBarcodeOk returns a tuple with the Barcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBarcode

`func (o *Product) SetBarcode(v string)`

SetBarcode sets Barcode field to given value.

### HasBarcode

`func (o *Product) HasBarcode() bool`

HasBarcode returns a boolean if a field has been set.

### SetBarcodeNil

`func (o *Product) SetBarcodeNil(b bool)`

 SetBarcodeNil sets the value for Barcode to be an explicit nil

### UnsetBarcode
`func (o *Product) UnsetBarcode()`

UnsetBarcode ensures that no value is present for Barcode, not even an explicit nil
### GetBrand

`func (o *Product) GetBrand() string`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *Product) GetBrandOk() (*string, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *Product) SetBrand(v string)`

SetBrand sets Brand field to given value.

### HasBrand

`func (o *Product) HasBrand() bool`

HasBrand returns a boolean if a field has been set.

### SetBrandNil

`func (o *Product) SetBrandNil(b bool)`

 SetBrandNil sets the value for Brand to be an explicit nil

### UnsetBrand
`func (o *Product) UnsetBrand()`

UnsetBrand ensures that no value is present for Brand, not even an explicit nil
### GetCategoryId

`func (o *Product) GetCategoryId() string`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *Product) GetCategoryIdOk() (*string, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *Product) SetCategoryId(v string)`

SetCategoryId sets CategoryId field to given value.

### HasCategoryId

`func (o *Product) HasCategoryId() bool`

HasCategoryId returns a boolean if a field has been set.

### SetCategoryIdNil

`func (o *Product) SetCategoryIdNil(b bool)`

 SetCategoryIdNil sets the value for CategoryId to be an explicit nil

### UnsetCategoryId
`func (o *Product) UnsetCategoryId()`

UnsetCategoryId ensures that no value is present for CategoryId, not even an explicit nil
### GetCondition

`func (o *Product) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *Product) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *Product) SetCondition(v string)`

SetCondition sets Condition field to given value.

### HasCondition

`func (o *Product) HasCondition() bool`

HasCondition returns a boolean if a field has been set.

### SetConditionNil

`func (o *Product) SetConditionNil(b bool)`

 SetConditionNil sets the value for Condition to be an explicit nil

### UnsetCondition
`func (o *Product) UnsetCondition()`

UnsetCondition ensures that no value is present for Condition, not even an explicit nil
### GetDefaultLedgerAccount

`func (o *Product) GetDefaultLedgerAccount() string`

GetDefaultLedgerAccount returns the DefaultLedgerAccount field if non-nil, zero value otherwise.

### GetDefaultLedgerAccountOk

`func (o *Product) GetDefaultLedgerAccountOk() (*string, bool)`

GetDefaultLedgerAccountOk returns a tuple with the DefaultLedgerAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultLedgerAccount

`func (o *Product) SetDefaultLedgerAccount(v string)`

SetDefaultLedgerAccount sets DefaultLedgerAccount field to given value.

### HasDefaultLedgerAccount

`func (o *Product) HasDefaultLedgerAccount() bool`

HasDefaultLedgerAccount returns a boolean if a field has been set.

### SetDefaultLedgerAccountNil

`func (o *Product) SetDefaultLedgerAccountNil(b bool)`

 SetDefaultLedgerAccountNil sets the value for DefaultLedgerAccount to be an explicit nil

### UnsetDefaultLedgerAccount
`func (o *Product) UnsetDefaultLedgerAccount()`

UnsetDefaultLedgerAccount ensures that no value is present for DefaultLedgerAccount, not even an explicit nil
### GetDefaultPrice

`func (o *Product) GetDefaultPrice() string`

GetDefaultPrice returns the DefaultPrice field if non-nil, zero value otherwise.

### GetDefaultPriceOk

`func (o *Product) GetDefaultPriceOk() (*string, bool)`

GetDefaultPriceOk returns a tuple with the DefaultPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultPrice

`func (o *Product) SetDefaultPrice(v string)`

SetDefaultPrice sets DefaultPrice field to given value.

### HasDefaultPrice

`func (o *Product) HasDefaultPrice() bool`

HasDefaultPrice returns a boolean if a field has been set.

### SetDefaultPriceNil

`func (o *Product) SetDefaultPriceNil(b bool)`

 SetDefaultPriceNil sets the value for DefaultPrice to be an explicit nil

### UnsetDefaultPrice
`func (o *Product) UnsetDefaultPrice()`

UnsetDefaultPrice ensures that no value is present for DefaultPrice, not even an explicit nil
### GetDefaultPriceFormulaId

`func (o *Product) GetDefaultPriceFormulaId() string`

GetDefaultPriceFormulaId returns the DefaultPriceFormulaId field if non-nil, zero value otherwise.

### GetDefaultPriceFormulaIdOk

`func (o *Product) GetDefaultPriceFormulaIdOk() (*string, bool)`

GetDefaultPriceFormulaIdOk returns a tuple with the DefaultPriceFormulaId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultPriceFormulaId

`func (o *Product) SetDefaultPriceFormulaId(v string)`

SetDefaultPriceFormulaId sets DefaultPriceFormulaId field to given value.

### HasDefaultPriceFormulaId

`func (o *Product) HasDefaultPriceFormulaId() bool`

HasDefaultPriceFormulaId returns a boolean if a field has been set.

### SetDefaultPriceFormulaIdNil

`func (o *Product) SetDefaultPriceFormulaIdNil(b bool)`

 SetDefaultPriceFormulaIdNil sets the value for DefaultPriceFormulaId to be an explicit nil

### UnsetDefaultPriceFormulaId
`func (o *Product) UnsetDefaultPriceFormulaId()`

UnsetDefaultPriceFormulaId ensures that no value is present for DefaultPriceFormulaId, not even an explicit nil
### GetDefaultTaxRate

`func (o *Product) GetDefaultTaxRate() string`

GetDefaultTaxRate returns the DefaultTaxRate field if non-nil, zero value otherwise.

### GetDefaultTaxRateOk

`func (o *Product) GetDefaultTaxRateOk() (*string, bool)`

GetDefaultTaxRateOk returns a tuple with the DefaultTaxRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultTaxRate

`func (o *Product) SetDefaultTaxRate(v string)`

SetDefaultTaxRate sets DefaultTaxRate field to given value.

### HasDefaultTaxRate

`func (o *Product) HasDefaultTaxRate() bool`

HasDefaultTaxRate returns a boolean if a field has been set.

### SetDefaultTaxRateNil

`func (o *Product) SetDefaultTaxRateNil(b bool)`

 SetDefaultTaxRateNil sets the value for DefaultTaxRate to be an explicit nil

### UnsetDefaultTaxRate
`func (o *Product) UnsetDefaultTaxRate()`

UnsetDefaultTaxRate ensures that no value is present for DefaultTaxRate, not even an explicit nil
### GetDescription

`func (o *Product) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Product) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Product) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Product) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *Product) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *Product) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetGtin

`func (o *Product) GetGtin() string`

GetGtin returns the Gtin field if non-nil, zero value otherwise.

### GetGtinOk

`func (o *Product) GetGtinOk() (*string, bool)`

GetGtinOk returns a tuple with the Gtin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGtin

`func (o *Product) SetGtin(v string)`

SetGtin sets Gtin field to given value.

### HasGtin

`func (o *Product) HasGtin() bool`

HasGtin returns a boolean if a field has been set.

### SetGtinNil

`func (o *Product) SetGtinNil(b bool)`

 SetGtinNil sets the value for Gtin to be an explicit nil

### UnsetGtin
`func (o *Product) UnsetGtin()`

UnsetGtin ensures that no value is present for Gtin, not even an explicit nil
### GetHeight

`func (o *Product) GetHeight() string`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *Product) GetHeightOk() (*string, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *Product) SetHeight(v string)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *Product) HasHeight() bool`

HasHeight returns a boolean if a field has been set.

### SetHeightNil

`func (o *Product) SetHeightNil(b bool)`

 SetHeightNil sets the value for Height to be an explicit nil

### UnsetHeight
`func (o *Product) UnsetHeight()`

UnsetHeight ensures that no value is present for Height, not even an explicit nil
### GetImageLink

`func (o *Product) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *Product) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *Product) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *Product) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### SetImageLinkNil

`func (o *Product) SetImageLinkNil(b bool)`

 SetImageLinkNil sets the value for ImageLink to be an explicit nil

### UnsetImageLink
`func (o *Product) UnsetImageLink()`

UnsetImageLink ensures that no value is present for ImageLink, not even an explicit nil
### GetImages

`func (o *Product) GetImages() interface{}`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *Product) GetImagesOk() (*interface{}, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *Product) SetImages(v interface{})`

SetImages sets Images field to given value.

### HasImages

`func (o *Product) HasImages() bool`

HasImages returns a boolean if a field has been set.

### SetImagesNil

`func (o *Product) SetImagesNil(b bool)`

 SetImagesNil sets the value for Images to be an explicit nil

### UnsetImages
`func (o *Product) UnsetImages()`

UnsetImages ensures that no value is present for Images, not even an explicit nil
### GetIsTaxable

`func (o *Product) GetIsTaxable() bool`

GetIsTaxable returns the IsTaxable field if non-nil, zero value otherwise.

### GetIsTaxableOk

`func (o *Product) GetIsTaxableOk() (*bool, bool)`

GetIsTaxableOk returns a tuple with the IsTaxable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTaxable

`func (o *Product) SetIsTaxable(v bool)`

SetIsTaxable sets IsTaxable field to given value.

### HasIsTaxable

`func (o *Product) HasIsTaxable() bool`

HasIsTaxable returns a boolean if a field has been set.

### GetLength

`func (o *Product) GetLength() string`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *Product) GetLengthOk() (*string, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *Product) SetLength(v string)`

SetLength sets Length field to given value.

### HasLength

`func (o *Product) HasLength() bool`

HasLength returns a boolean if a field has been set.

### SetLengthNil

`func (o *Product) SetLengthNil(b bool)`

 SetLengthNil sets the value for Length to be an explicit nil

### UnsetLength
`func (o *Product) UnsetLength()`

UnsetLength ensures that no value is present for Length, not even an explicit nil
### GetLink

`func (o *Product) GetLink() string`

GetLink returns the Link field if non-nil, zero value otherwise.

### GetLinkOk

`func (o *Product) GetLinkOk() (*string, bool)`

GetLinkOk returns a tuple with the Link field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLink

`func (o *Product) SetLink(v string)`

SetLink sets Link field to given value.

### HasLink

`func (o *Product) HasLink() bool`

HasLink returns a boolean if a field has been set.

### SetLinkNil

`func (o *Product) SetLinkNil(b bool)`

 SetLinkNil sets the value for Link to be an explicit nil

### UnsetLink
`func (o *Product) UnsetLink()`

UnsetLink ensures that no value is present for Link, not even an explicit nil
### GetMaxStock

`func (o *Product) GetMaxStock() int64`

GetMaxStock returns the MaxStock field if non-nil, zero value otherwise.

### GetMaxStockOk

`func (o *Product) GetMaxStockOk() (*int64, bool)`

GetMaxStockOk returns a tuple with the MaxStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxStock

`func (o *Product) SetMaxStock(v int64)`

SetMaxStock sets MaxStock field to given value.

### HasMaxStock

`func (o *Product) HasMaxStock() bool`

HasMaxStock returns a boolean if a field has been set.

### SetMaxStockNil

`func (o *Product) SetMaxStockNil(b bool)`

 SetMaxStockNil sets the value for MaxStock to be an explicit nil

### UnsetMaxStock
`func (o *Product) UnsetMaxStock()`

UnsetMaxStock ensures that no value is present for MaxStock, not even an explicit nil
### GetMinStock

`func (o *Product) GetMinStock() int64`

GetMinStock returns the MinStock field if non-nil, zero value otherwise.

### GetMinStockOk

`func (o *Product) GetMinStockOk() (*int64, bool)`

GetMinStockOk returns a tuple with the MinStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinStock

`func (o *Product) SetMinStock(v int64)`

SetMinStock sets MinStock field to given value.

### HasMinStock

`func (o *Product) HasMinStock() bool`

HasMinStock returns a boolean if a field has been set.

### SetMinStockNil

`func (o *Product) SetMinStockNil(b bool)`

 SetMinStockNil sets the value for MinStock to be an explicit nil

### UnsetMinStock
`func (o *Product) UnsetMinStock()`

UnsetMinStock ensures that no value is present for MinStock, not even an explicit nil
### GetMpn

`func (o *Product) GetMpn() string`

GetMpn returns the Mpn field if non-nil, zero value otherwise.

### GetMpnOk

`func (o *Product) GetMpnOk() (*string, bool)`

GetMpnOk returns a tuple with the Mpn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMpn

`func (o *Product) SetMpn(v string)`

SetMpn sets Mpn field to given value.

### HasMpn

`func (o *Product) HasMpn() bool`

HasMpn returns a boolean if a field has been set.

### SetMpnNil

`func (o *Product) SetMpnNil(b bool)`

 SetMpnNil sets the value for Mpn to be an explicit nil

### UnsetMpn
`func (o *Product) UnsetMpn()`

UnsetMpn ensures that no value is present for Mpn, not even an explicit nil
### GetName

`func (o *Product) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Product) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Product) SetName(v string)`

SetName sets Name field to given value.


### GetPackageHeight

`func (o *Product) GetPackageHeight() string`

GetPackageHeight returns the PackageHeight field if non-nil, zero value otherwise.

### GetPackageHeightOk

`func (o *Product) GetPackageHeightOk() (*string, bool)`

GetPackageHeightOk returns a tuple with the PackageHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageHeight

`func (o *Product) SetPackageHeight(v string)`

SetPackageHeight sets PackageHeight field to given value.

### HasPackageHeight

`func (o *Product) HasPackageHeight() bool`

HasPackageHeight returns a boolean if a field has been set.

### SetPackageHeightNil

`func (o *Product) SetPackageHeightNil(b bool)`

 SetPackageHeightNil sets the value for PackageHeight to be an explicit nil

### UnsetPackageHeight
`func (o *Product) UnsetPackageHeight()`

UnsetPackageHeight ensures that no value is present for PackageHeight, not even an explicit nil
### GetPackageLength

`func (o *Product) GetPackageLength() string`

GetPackageLength returns the PackageLength field if non-nil, zero value otherwise.

### GetPackageLengthOk

`func (o *Product) GetPackageLengthOk() (*string, bool)`

GetPackageLengthOk returns a tuple with the PackageLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageLength

`func (o *Product) SetPackageLength(v string)`

SetPackageLength sets PackageLength field to given value.

### HasPackageLength

`func (o *Product) HasPackageLength() bool`

HasPackageLength returns a boolean if a field has been set.

### SetPackageLengthNil

`func (o *Product) SetPackageLengthNil(b bool)`

 SetPackageLengthNil sets the value for PackageLength to be an explicit nil

### UnsetPackageLength
`func (o *Product) UnsetPackageLength()`

UnsetPackageLength ensures that no value is present for PackageLength, not even an explicit nil
### GetPackageWeightUnit

`func (o *Product) GetPackageWeightUnit() string`

GetPackageWeightUnit returns the PackageWeightUnit field if non-nil, zero value otherwise.

### GetPackageWeightUnitOk

`func (o *Product) GetPackageWeightUnitOk() (*string, bool)`

GetPackageWeightUnitOk returns a tuple with the PackageWeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageWeightUnit

`func (o *Product) SetPackageWeightUnit(v string)`

SetPackageWeightUnit sets PackageWeightUnit field to given value.

### HasPackageWeightUnit

`func (o *Product) HasPackageWeightUnit() bool`

HasPackageWeightUnit returns a boolean if a field has been set.

### SetPackageWeightUnitNil

`func (o *Product) SetPackageWeightUnitNil(b bool)`

 SetPackageWeightUnitNil sets the value for PackageWeightUnit to be an explicit nil

### UnsetPackageWeightUnit
`func (o *Product) UnsetPackageWeightUnit()`

UnsetPackageWeightUnit ensures that no value is present for PackageWeightUnit, not even an explicit nil
### GetPackageWeightValue

`func (o *Product) GetPackageWeightValue() string`

GetPackageWeightValue returns the PackageWeightValue field if non-nil, zero value otherwise.

### GetPackageWeightValueOk

`func (o *Product) GetPackageWeightValueOk() (*string, bool)`

GetPackageWeightValueOk returns a tuple with the PackageWeightValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageWeightValue

`func (o *Product) SetPackageWeightValue(v string)`

SetPackageWeightValue sets PackageWeightValue field to given value.

### HasPackageWeightValue

`func (o *Product) HasPackageWeightValue() bool`

HasPackageWeightValue returns a boolean if a field has been set.

### SetPackageWeightValueNil

`func (o *Product) SetPackageWeightValueNil(b bool)`

 SetPackageWeightValueNil sets the value for PackageWeightValue to be an explicit nil

### UnsetPackageWeightValue
`func (o *Product) UnsetPackageWeightValue()`

UnsetPackageWeightValue ensures that no value is present for PackageWeightValue, not even an explicit nil
### GetPackageWidth

`func (o *Product) GetPackageWidth() string`

GetPackageWidth returns the PackageWidth field if non-nil, zero value otherwise.

### GetPackageWidthOk

`func (o *Product) GetPackageWidthOk() (*string, bool)`

GetPackageWidthOk returns a tuple with the PackageWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageWidth

`func (o *Product) SetPackageWidth(v string)`

SetPackageWidth sets PackageWidth field to given value.

### HasPackageWidth

`func (o *Product) HasPackageWidth() bool`

HasPackageWidth returns a boolean if a field has been set.

### SetPackageWidthNil

`func (o *Product) SetPackageWidthNil(b bool)`

 SetPackageWidthNil sets the value for PackageWidth to be an explicit nil

### UnsetPackageWidth
`func (o *Product) UnsetPackageWidth()`

UnsetPackageWidth ensures that no value is present for PackageWidth, not even an explicit nil
### GetProductCode

`func (o *Product) GetProductCode() string`

GetProductCode returns the ProductCode field if non-nil, zero value otherwise.

### GetProductCodeOk

`func (o *Product) GetProductCodeOk() (*string, bool)`

GetProductCodeOk returns a tuple with the ProductCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductCode

`func (o *Product) SetProductCode(v string)`

SetProductCode sets ProductCode field to given value.


### GetProductType

`func (o *Product) GetProductType() string`

GetProductType returns the ProductType field if non-nil, zero value otherwise.

### GetProductTypeOk

`func (o *Product) GetProductTypeOk() (*string, bool)`

GetProductTypeOk returns a tuple with the ProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductType

`func (o *Product) SetProductType(v string)`

SetProductType sets ProductType field to given value.

### HasProductType

`func (o *Product) HasProductType() bool`

HasProductType returns a boolean if a field has been set.

### SetProductTypeNil

`func (o *Product) SetProductTypeNil(b bool)`

 SetProductTypeNil sets the value for ProductType to be an explicit nil

### UnsetProductType
`func (o *Product) UnsetProductType()`

UnsetProductType ensures that no value is present for ProductType, not even an explicit nil
### GetPurchasePrice

`func (o *Product) GetPurchasePrice() string`

GetPurchasePrice returns the PurchasePrice field if non-nil, zero value otherwise.

### GetPurchasePriceOk

`func (o *Product) GetPurchasePriceOk() (*string, bool)`

GetPurchasePriceOk returns a tuple with the PurchasePrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchasePrice

`func (o *Product) SetPurchasePrice(v string)`

SetPurchasePrice sets PurchasePrice field to given value.

### HasPurchasePrice

`func (o *Product) HasPurchasePrice() bool`

HasPurchasePrice returns a boolean if a field has been set.

### SetPurchasePriceNil

`func (o *Product) SetPurchasePriceNil(b bool)`

 SetPurchasePriceNil sets the value for PurchasePrice to be an explicit nil

### UnsetPurchasePrice
`func (o *Product) UnsetPurchasePrice()`

UnsetPurchasePrice ensures that no value is present for PurchasePrice, not even an explicit nil
### GetReorderQuantity

`func (o *Product) GetReorderQuantity() int64`

GetReorderQuantity returns the ReorderQuantity field if non-nil, zero value otherwise.

### GetReorderQuantityOk

`func (o *Product) GetReorderQuantityOk() (*int64, bool)`

GetReorderQuantityOk returns a tuple with the ReorderQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReorderQuantity

`func (o *Product) SetReorderQuantity(v int64)`

SetReorderQuantity sets ReorderQuantity field to given value.

### HasReorderQuantity

`func (o *Product) HasReorderQuantity() bool`

HasReorderQuantity returns a boolean if a field has been set.

### SetReorderQuantityNil

`func (o *Product) SetReorderQuantityNil(b bool)`

 SetReorderQuantityNil sets the value for ReorderQuantity to be an explicit nil

### UnsetReorderQuantity
`func (o *Product) UnsetReorderQuantity()`

UnsetReorderQuantity ensures that no value is present for ReorderQuantity, not even an explicit nil
### GetSalePrice

`func (o *Product) GetSalePrice() string`

GetSalePrice returns the SalePrice field if non-nil, zero value otherwise.

### GetSalePriceOk

`func (o *Product) GetSalePriceOk() (*string, bool)`

GetSalePriceOk returns a tuple with the SalePrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalePrice

`func (o *Product) SetSalePrice(v string)`

SetSalePrice sets SalePrice field to given value.

### HasSalePrice

`func (o *Product) HasSalePrice() bool`

HasSalePrice returns a boolean if a field has been set.

### SetSalePriceNil

`func (o *Product) SetSalePriceNil(b bool)`

 SetSalePriceNil sets the value for SalePrice to be an explicit nil

### UnsetSalePrice
`func (o *Product) UnsetSalePrice()`

UnsetSalePrice ensures that no value is present for SalePrice, not even an explicit nil
### GetShippingPrice

`func (o *Product) GetShippingPrice() string`

GetShippingPrice returns the ShippingPrice field if non-nil, zero value otherwise.

### GetShippingPriceOk

`func (o *Product) GetShippingPriceOk() (*string, bool)`

GetShippingPriceOk returns a tuple with the ShippingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingPrice

`func (o *Product) SetShippingPrice(v string)`

SetShippingPrice sets ShippingPrice field to given value.

### HasShippingPrice

`func (o *Product) HasShippingPrice() bool`

HasShippingPrice returns a boolean if a field has been set.

### SetShippingPriceNil

`func (o *Product) SetShippingPriceNil(b bool)`

 SetShippingPriceNil sets the value for ShippingPrice to be an explicit nil

### UnsetShippingPrice
`func (o *Product) UnsetShippingPrice()`

UnsetShippingPrice ensures that no value is present for ShippingPrice, not even an explicit nil
### GetShippingRequiresInsurance

`func (o *Product) GetShippingRequiresInsurance() bool`

GetShippingRequiresInsurance returns the ShippingRequiresInsurance field if non-nil, zero value otherwise.

### GetShippingRequiresInsuranceOk

`func (o *Product) GetShippingRequiresInsuranceOk() (*bool, bool)`

GetShippingRequiresInsuranceOk returns a tuple with the ShippingRequiresInsurance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRequiresInsurance

`func (o *Product) SetShippingRequiresInsurance(v bool)`

SetShippingRequiresInsurance sets ShippingRequiresInsurance field to given value.

### HasShippingRequiresInsurance

`func (o *Product) HasShippingRequiresInsurance() bool`

HasShippingRequiresInsurance returns a boolean if a field has been set.

### SetShippingRequiresInsuranceNil

`func (o *Product) SetShippingRequiresInsuranceNil(b bool)`

 SetShippingRequiresInsuranceNil sets the value for ShippingRequiresInsurance to be an explicit nil

### UnsetShippingRequiresInsurance
`func (o *Product) UnsetShippingRequiresInsurance()`

UnsetShippingRequiresInsurance ensures that no value is present for ShippingRequiresInsurance, not even an explicit nil
### GetSku

`func (o *Product) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *Product) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *Product) SetSku(v string)`

SetSku sets Sku field to given value.


### GetStockQuantity

`func (o *Product) GetStockQuantity() int64`

GetStockQuantity returns the StockQuantity field if non-nil, zero value otherwise.

### GetStockQuantityOk

`func (o *Product) GetStockQuantityOk() (*int64, bool)`

GetStockQuantityOk returns a tuple with the StockQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStockQuantity

`func (o *Product) SetStockQuantity(v int64)`

SetStockQuantity sets StockQuantity field to given value.

### HasStockQuantity

`func (o *Product) HasStockQuantity() bool`

HasStockQuantity returns a boolean if a field has been set.

### SetStockQuantityNil

`func (o *Product) SetStockQuantityNil(b bool)`

 SetStockQuantityNil sets the value for StockQuantity to be an explicit nil

### UnsetStockQuantity
`func (o *Product) UnsetStockQuantity()`

UnsetStockQuantity ensures that no value is present for StockQuantity, not even an explicit nil
### GetTags

`func (o *Product) GetTags() interface{}`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *Product) GetTagsOk() (*interface{}, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *Product) SetTags(v interface{})`

SetTags sets Tags field to given value.

### HasTags

`func (o *Product) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *Product) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *Product) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTaxPrice

`func (o *Product) GetTaxPrice() string`

GetTaxPrice returns the TaxPrice field if non-nil, zero value otherwise.

### GetTaxPriceOk

`func (o *Product) GetTaxPriceOk() (*string, bool)`

GetTaxPriceOk returns a tuple with the TaxPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxPrice

`func (o *Product) SetTaxPrice(v string)`

SetTaxPrice sets TaxPrice field to given value.

### HasTaxPrice

`func (o *Product) HasTaxPrice() bool`

HasTaxPrice returns a boolean if a field has been set.

### SetTaxPriceNil

`func (o *Product) SetTaxPriceNil(b bool)`

 SetTaxPriceNil sets the value for TaxPrice to be an explicit nil

### UnsetTaxPrice
`func (o *Product) UnsetTaxPrice()`

UnsetTaxPrice ensures that no value is present for TaxPrice, not even an explicit nil
### GetTrackBatch

`func (o *Product) GetTrackBatch() bool`

GetTrackBatch returns the TrackBatch field if non-nil, zero value otherwise.

### GetTrackBatchOk

`func (o *Product) GetTrackBatchOk() (*bool, bool)`

GetTrackBatchOk returns a tuple with the TrackBatch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackBatch

`func (o *Product) SetTrackBatch(v bool)`

SetTrackBatch sets TrackBatch field to given value.

### HasTrackBatch

`func (o *Product) HasTrackBatch() bool`

HasTrackBatch returns a boolean if a field has been set.

### GetTrackSerial

`func (o *Product) GetTrackSerial() bool`

GetTrackSerial returns the TrackSerial field if non-nil, zero value otherwise.

### GetTrackSerialOk

`func (o *Product) GetTrackSerialOk() (*bool, bool)`

GetTrackSerialOk returns a tuple with the TrackSerial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackSerial

`func (o *Product) SetTrackSerial(v bool)`

SetTrackSerial sets TrackSerial field to given value.

### HasTrackSerial

`func (o *Product) HasTrackSerial() bool`

HasTrackSerial returns a boolean if a field has been set.

### GetUnit

`func (o *Product) GetUnit() interface{}`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *Product) GetUnitOk() (*interface{}, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *Product) SetUnit(v interface{})`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *Product) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### SetUnitNil

`func (o *Product) SetUnitNil(b bool)`

 SetUnitNil sets the value for Unit to be an explicit nil

### UnsetUnit
`func (o *Product) UnsetUnit()`

UnsetUnit ensures that no value is present for Unit, not even an explicit nil
### GetWeightUnit

`func (o *Product) GetWeightUnit() string`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *Product) GetWeightUnitOk() (*string, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *Product) SetWeightUnit(v string)`

SetWeightUnit sets WeightUnit field to given value.

### HasWeightUnit

`func (o *Product) HasWeightUnit() bool`

HasWeightUnit returns a boolean if a field has been set.

### SetWeightUnitNil

`func (o *Product) SetWeightUnitNil(b bool)`

 SetWeightUnitNil sets the value for WeightUnit to be an explicit nil

### UnsetWeightUnit
`func (o *Product) UnsetWeightUnit()`

UnsetWeightUnit ensures that no value is present for WeightUnit, not even an explicit nil
### GetWeightValue

`func (o *Product) GetWeightValue() string`

GetWeightValue returns the WeightValue field if non-nil, zero value otherwise.

### GetWeightValueOk

`func (o *Product) GetWeightValueOk() (*string, bool)`

GetWeightValueOk returns a tuple with the WeightValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightValue

`func (o *Product) SetWeightValue(v string)`

SetWeightValue sets WeightValue field to given value.

### HasWeightValue

`func (o *Product) HasWeightValue() bool`

HasWeightValue returns a boolean if a field has been set.

### SetWeightValueNil

`func (o *Product) SetWeightValueNil(b bool)`

 SetWeightValueNil sets the value for WeightValue to be an explicit nil

### UnsetWeightValue
`func (o *Product) UnsetWeightValue()`

UnsetWeightValue ensures that no value is present for WeightValue, not even an explicit nil
### GetWidth

`func (o *Product) GetWidth() string`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *Product) GetWidthOk() (*string, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *Product) SetWidth(v string)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *Product) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### SetWidthNil

`func (o *Product) SetWidthNil(b bool)`

 SetWidthNil sets the value for Width to be an explicit nil

### UnsetWidth
`func (o *Product) UnsetWidth()`

UnsetWidth ensures that no value is present for Width, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


