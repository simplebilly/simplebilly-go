# ProductCreate

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

### NewProductCreate

`func NewProductCreate(name string, productCode string, sku string, ) *ProductCreate`

NewProductCreate instantiates a new ProductCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductCreateWithDefaults

`func NewProductCreateWithDefaults() *ProductCreate`

NewProductCreateWithDefaults instantiates a new ProductCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvailability

`func (o *ProductCreate) GetAvailability() string`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *ProductCreate) GetAvailabilityOk() (*string, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *ProductCreate) SetAvailability(v string)`

SetAvailability sets Availability field to given value.

### HasAvailability

`func (o *ProductCreate) HasAvailability() bool`

HasAvailability returns a boolean if a field has been set.

### SetAvailabilityNil

`func (o *ProductCreate) SetAvailabilityNil(b bool)`

 SetAvailabilityNil sets the value for Availability to be an explicit nil

### UnsetAvailability
`func (o *ProductCreate) UnsetAvailability()`

UnsetAvailability ensures that no value is present for Availability, not even an explicit nil
### GetBarcode

`func (o *ProductCreate) GetBarcode() string`

GetBarcode returns the Barcode field if non-nil, zero value otherwise.

### GetBarcodeOk

`func (o *ProductCreate) GetBarcodeOk() (*string, bool)`

GetBarcodeOk returns a tuple with the Barcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBarcode

`func (o *ProductCreate) SetBarcode(v string)`

SetBarcode sets Barcode field to given value.

### HasBarcode

`func (o *ProductCreate) HasBarcode() bool`

HasBarcode returns a boolean if a field has been set.

### SetBarcodeNil

`func (o *ProductCreate) SetBarcodeNil(b bool)`

 SetBarcodeNil sets the value for Barcode to be an explicit nil

### UnsetBarcode
`func (o *ProductCreate) UnsetBarcode()`

UnsetBarcode ensures that no value is present for Barcode, not even an explicit nil
### GetBrand

`func (o *ProductCreate) GetBrand() string`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *ProductCreate) GetBrandOk() (*string, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *ProductCreate) SetBrand(v string)`

SetBrand sets Brand field to given value.

### HasBrand

`func (o *ProductCreate) HasBrand() bool`

HasBrand returns a boolean if a field has been set.

### SetBrandNil

`func (o *ProductCreate) SetBrandNil(b bool)`

 SetBrandNil sets the value for Brand to be an explicit nil

### UnsetBrand
`func (o *ProductCreate) UnsetBrand()`

UnsetBrand ensures that no value is present for Brand, not even an explicit nil
### GetCategoryId

`func (o *ProductCreate) GetCategoryId() string`

GetCategoryId returns the CategoryId field if non-nil, zero value otherwise.

### GetCategoryIdOk

`func (o *ProductCreate) GetCategoryIdOk() (*string, bool)`

GetCategoryIdOk returns a tuple with the CategoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategoryId

`func (o *ProductCreate) SetCategoryId(v string)`

SetCategoryId sets CategoryId field to given value.

### HasCategoryId

`func (o *ProductCreate) HasCategoryId() bool`

HasCategoryId returns a boolean if a field has been set.

### SetCategoryIdNil

`func (o *ProductCreate) SetCategoryIdNil(b bool)`

 SetCategoryIdNil sets the value for CategoryId to be an explicit nil

### UnsetCategoryId
`func (o *ProductCreate) UnsetCategoryId()`

UnsetCategoryId ensures that no value is present for CategoryId, not even an explicit nil
### GetCondition

`func (o *ProductCreate) GetCondition() string`

GetCondition returns the Condition field if non-nil, zero value otherwise.

### GetConditionOk

`func (o *ProductCreate) GetConditionOk() (*string, bool)`

GetConditionOk returns a tuple with the Condition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCondition

`func (o *ProductCreate) SetCondition(v string)`

SetCondition sets Condition field to given value.

### HasCondition

`func (o *ProductCreate) HasCondition() bool`

HasCondition returns a boolean if a field has been set.

### SetConditionNil

`func (o *ProductCreate) SetConditionNil(b bool)`

 SetConditionNil sets the value for Condition to be an explicit nil

### UnsetCondition
`func (o *ProductCreate) UnsetCondition()`

UnsetCondition ensures that no value is present for Condition, not even an explicit nil
### GetDefaultLedgerAccount

`func (o *ProductCreate) GetDefaultLedgerAccount() string`

GetDefaultLedgerAccount returns the DefaultLedgerAccount field if non-nil, zero value otherwise.

### GetDefaultLedgerAccountOk

`func (o *ProductCreate) GetDefaultLedgerAccountOk() (*string, bool)`

GetDefaultLedgerAccountOk returns a tuple with the DefaultLedgerAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultLedgerAccount

`func (o *ProductCreate) SetDefaultLedgerAccount(v string)`

SetDefaultLedgerAccount sets DefaultLedgerAccount field to given value.

### HasDefaultLedgerAccount

`func (o *ProductCreate) HasDefaultLedgerAccount() bool`

HasDefaultLedgerAccount returns a boolean if a field has been set.

### SetDefaultLedgerAccountNil

`func (o *ProductCreate) SetDefaultLedgerAccountNil(b bool)`

 SetDefaultLedgerAccountNil sets the value for DefaultLedgerAccount to be an explicit nil

### UnsetDefaultLedgerAccount
`func (o *ProductCreate) UnsetDefaultLedgerAccount()`

UnsetDefaultLedgerAccount ensures that no value is present for DefaultLedgerAccount, not even an explicit nil
### GetDefaultPrice

`func (o *ProductCreate) GetDefaultPrice() string`

GetDefaultPrice returns the DefaultPrice field if non-nil, zero value otherwise.

### GetDefaultPriceOk

`func (o *ProductCreate) GetDefaultPriceOk() (*string, bool)`

GetDefaultPriceOk returns a tuple with the DefaultPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultPrice

`func (o *ProductCreate) SetDefaultPrice(v string)`

SetDefaultPrice sets DefaultPrice field to given value.

### HasDefaultPrice

`func (o *ProductCreate) HasDefaultPrice() bool`

HasDefaultPrice returns a boolean if a field has been set.

### SetDefaultPriceNil

`func (o *ProductCreate) SetDefaultPriceNil(b bool)`

 SetDefaultPriceNil sets the value for DefaultPrice to be an explicit nil

### UnsetDefaultPrice
`func (o *ProductCreate) UnsetDefaultPrice()`

UnsetDefaultPrice ensures that no value is present for DefaultPrice, not even an explicit nil
### GetDefaultPriceFormulaId

`func (o *ProductCreate) GetDefaultPriceFormulaId() string`

GetDefaultPriceFormulaId returns the DefaultPriceFormulaId field if non-nil, zero value otherwise.

### GetDefaultPriceFormulaIdOk

`func (o *ProductCreate) GetDefaultPriceFormulaIdOk() (*string, bool)`

GetDefaultPriceFormulaIdOk returns a tuple with the DefaultPriceFormulaId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultPriceFormulaId

`func (o *ProductCreate) SetDefaultPriceFormulaId(v string)`

SetDefaultPriceFormulaId sets DefaultPriceFormulaId field to given value.

### HasDefaultPriceFormulaId

`func (o *ProductCreate) HasDefaultPriceFormulaId() bool`

HasDefaultPriceFormulaId returns a boolean if a field has been set.

### SetDefaultPriceFormulaIdNil

`func (o *ProductCreate) SetDefaultPriceFormulaIdNil(b bool)`

 SetDefaultPriceFormulaIdNil sets the value for DefaultPriceFormulaId to be an explicit nil

### UnsetDefaultPriceFormulaId
`func (o *ProductCreate) UnsetDefaultPriceFormulaId()`

UnsetDefaultPriceFormulaId ensures that no value is present for DefaultPriceFormulaId, not even an explicit nil
### GetDefaultTaxRate

`func (o *ProductCreate) GetDefaultTaxRate() string`

GetDefaultTaxRate returns the DefaultTaxRate field if non-nil, zero value otherwise.

### GetDefaultTaxRateOk

`func (o *ProductCreate) GetDefaultTaxRateOk() (*string, bool)`

GetDefaultTaxRateOk returns a tuple with the DefaultTaxRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultTaxRate

`func (o *ProductCreate) SetDefaultTaxRate(v string)`

SetDefaultTaxRate sets DefaultTaxRate field to given value.

### HasDefaultTaxRate

`func (o *ProductCreate) HasDefaultTaxRate() bool`

HasDefaultTaxRate returns a boolean if a field has been set.

### SetDefaultTaxRateNil

`func (o *ProductCreate) SetDefaultTaxRateNil(b bool)`

 SetDefaultTaxRateNil sets the value for DefaultTaxRate to be an explicit nil

### UnsetDefaultTaxRate
`func (o *ProductCreate) UnsetDefaultTaxRate()`

UnsetDefaultTaxRate ensures that no value is present for DefaultTaxRate, not even an explicit nil
### GetDescription

`func (o *ProductCreate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ProductCreate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ProductCreate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ProductCreate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ProductCreate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ProductCreate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetGtin

`func (o *ProductCreate) GetGtin() string`

GetGtin returns the Gtin field if non-nil, zero value otherwise.

### GetGtinOk

`func (o *ProductCreate) GetGtinOk() (*string, bool)`

GetGtinOk returns a tuple with the Gtin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGtin

`func (o *ProductCreate) SetGtin(v string)`

SetGtin sets Gtin field to given value.

### HasGtin

`func (o *ProductCreate) HasGtin() bool`

HasGtin returns a boolean if a field has been set.

### SetGtinNil

`func (o *ProductCreate) SetGtinNil(b bool)`

 SetGtinNil sets the value for Gtin to be an explicit nil

### UnsetGtin
`func (o *ProductCreate) UnsetGtin()`

UnsetGtin ensures that no value is present for Gtin, not even an explicit nil
### GetHeight

`func (o *ProductCreate) GetHeight() string`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *ProductCreate) GetHeightOk() (*string, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *ProductCreate) SetHeight(v string)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *ProductCreate) HasHeight() bool`

HasHeight returns a boolean if a field has been set.

### SetHeightNil

`func (o *ProductCreate) SetHeightNil(b bool)`

 SetHeightNil sets the value for Height to be an explicit nil

### UnsetHeight
`func (o *ProductCreate) UnsetHeight()`

UnsetHeight ensures that no value is present for Height, not even an explicit nil
### GetImageLink

`func (o *ProductCreate) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *ProductCreate) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *ProductCreate) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *ProductCreate) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### SetImageLinkNil

`func (o *ProductCreate) SetImageLinkNil(b bool)`

 SetImageLinkNil sets the value for ImageLink to be an explicit nil

### UnsetImageLink
`func (o *ProductCreate) UnsetImageLink()`

UnsetImageLink ensures that no value is present for ImageLink, not even an explicit nil
### GetImages

`func (o *ProductCreate) GetImages() interface{}`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *ProductCreate) GetImagesOk() (*interface{}, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *ProductCreate) SetImages(v interface{})`

SetImages sets Images field to given value.

### HasImages

`func (o *ProductCreate) HasImages() bool`

HasImages returns a boolean if a field has been set.

### SetImagesNil

`func (o *ProductCreate) SetImagesNil(b bool)`

 SetImagesNil sets the value for Images to be an explicit nil

### UnsetImages
`func (o *ProductCreate) UnsetImages()`

UnsetImages ensures that no value is present for Images, not even an explicit nil
### GetIsTaxable

`func (o *ProductCreate) GetIsTaxable() bool`

GetIsTaxable returns the IsTaxable field if non-nil, zero value otherwise.

### GetIsTaxableOk

`func (o *ProductCreate) GetIsTaxableOk() (*bool, bool)`

GetIsTaxableOk returns a tuple with the IsTaxable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTaxable

`func (o *ProductCreate) SetIsTaxable(v bool)`

SetIsTaxable sets IsTaxable field to given value.

### HasIsTaxable

`func (o *ProductCreate) HasIsTaxable() bool`

HasIsTaxable returns a boolean if a field has been set.

### GetLength

`func (o *ProductCreate) GetLength() string`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *ProductCreate) GetLengthOk() (*string, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *ProductCreate) SetLength(v string)`

SetLength sets Length field to given value.

### HasLength

`func (o *ProductCreate) HasLength() bool`

HasLength returns a boolean if a field has been set.

### SetLengthNil

`func (o *ProductCreate) SetLengthNil(b bool)`

 SetLengthNil sets the value for Length to be an explicit nil

### UnsetLength
`func (o *ProductCreate) UnsetLength()`

UnsetLength ensures that no value is present for Length, not even an explicit nil
### GetLink

`func (o *ProductCreate) GetLink() string`

GetLink returns the Link field if non-nil, zero value otherwise.

### GetLinkOk

`func (o *ProductCreate) GetLinkOk() (*string, bool)`

GetLinkOk returns a tuple with the Link field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLink

`func (o *ProductCreate) SetLink(v string)`

SetLink sets Link field to given value.

### HasLink

`func (o *ProductCreate) HasLink() bool`

HasLink returns a boolean if a field has been set.

### SetLinkNil

`func (o *ProductCreate) SetLinkNil(b bool)`

 SetLinkNil sets the value for Link to be an explicit nil

### UnsetLink
`func (o *ProductCreate) UnsetLink()`

UnsetLink ensures that no value is present for Link, not even an explicit nil
### GetMaxStock

`func (o *ProductCreate) GetMaxStock() int64`

GetMaxStock returns the MaxStock field if non-nil, zero value otherwise.

### GetMaxStockOk

`func (o *ProductCreate) GetMaxStockOk() (*int64, bool)`

GetMaxStockOk returns a tuple with the MaxStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxStock

`func (o *ProductCreate) SetMaxStock(v int64)`

SetMaxStock sets MaxStock field to given value.

### HasMaxStock

`func (o *ProductCreate) HasMaxStock() bool`

HasMaxStock returns a boolean if a field has been set.

### SetMaxStockNil

`func (o *ProductCreate) SetMaxStockNil(b bool)`

 SetMaxStockNil sets the value for MaxStock to be an explicit nil

### UnsetMaxStock
`func (o *ProductCreate) UnsetMaxStock()`

UnsetMaxStock ensures that no value is present for MaxStock, not even an explicit nil
### GetMinStock

`func (o *ProductCreate) GetMinStock() int64`

GetMinStock returns the MinStock field if non-nil, zero value otherwise.

### GetMinStockOk

`func (o *ProductCreate) GetMinStockOk() (*int64, bool)`

GetMinStockOk returns a tuple with the MinStock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinStock

`func (o *ProductCreate) SetMinStock(v int64)`

SetMinStock sets MinStock field to given value.

### HasMinStock

`func (o *ProductCreate) HasMinStock() bool`

HasMinStock returns a boolean if a field has been set.

### SetMinStockNil

`func (o *ProductCreate) SetMinStockNil(b bool)`

 SetMinStockNil sets the value for MinStock to be an explicit nil

### UnsetMinStock
`func (o *ProductCreate) UnsetMinStock()`

UnsetMinStock ensures that no value is present for MinStock, not even an explicit nil
### GetMpn

`func (o *ProductCreate) GetMpn() string`

GetMpn returns the Mpn field if non-nil, zero value otherwise.

### GetMpnOk

`func (o *ProductCreate) GetMpnOk() (*string, bool)`

GetMpnOk returns a tuple with the Mpn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMpn

`func (o *ProductCreate) SetMpn(v string)`

SetMpn sets Mpn field to given value.

### HasMpn

`func (o *ProductCreate) HasMpn() bool`

HasMpn returns a boolean if a field has been set.

### SetMpnNil

`func (o *ProductCreate) SetMpnNil(b bool)`

 SetMpnNil sets the value for Mpn to be an explicit nil

### UnsetMpn
`func (o *ProductCreate) UnsetMpn()`

UnsetMpn ensures that no value is present for Mpn, not even an explicit nil
### GetName

`func (o *ProductCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductCreate) SetName(v string)`

SetName sets Name field to given value.


### GetPackageHeight

`func (o *ProductCreate) GetPackageHeight() string`

GetPackageHeight returns the PackageHeight field if non-nil, zero value otherwise.

### GetPackageHeightOk

`func (o *ProductCreate) GetPackageHeightOk() (*string, bool)`

GetPackageHeightOk returns a tuple with the PackageHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageHeight

`func (o *ProductCreate) SetPackageHeight(v string)`

SetPackageHeight sets PackageHeight field to given value.

### HasPackageHeight

`func (o *ProductCreate) HasPackageHeight() bool`

HasPackageHeight returns a boolean if a field has been set.

### SetPackageHeightNil

`func (o *ProductCreate) SetPackageHeightNil(b bool)`

 SetPackageHeightNil sets the value for PackageHeight to be an explicit nil

### UnsetPackageHeight
`func (o *ProductCreate) UnsetPackageHeight()`

UnsetPackageHeight ensures that no value is present for PackageHeight, not even an explicit nil
### GetPackageLength

`func (o *ProductCreate) GetPackageLength() string`

GetPackageLength returns the PackageLength field if non-nil, zero value otherwise.

### GetPackageLengthOk

`func (o *ProductCreate) GetPackageLengthOk() (*string, bool)`

GetPackageLengthOk returns a tuple with the PackageLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageLength

`func (o *ProductCreate) SetPackageLength(v string)`

SetPackageLength sets PackageLength field to given value.

### HasPackageLength

`func (o *ProductCreate) HasPackageLength() bool`

HasPackageLength returns a boolean if a field has been set.

### SetPackageLengthNil

`func (o *ProductCreate) SetPackageLengthNil(b bool)`

 SetPackageLengthNil sets the value for PackageLength to be an explicit nil

### UnsetPackageLength
`func (o *ProductCreate) UnsetPackageLength()`

UnsetPackageLength ensures that no value is present for PackageLength, not even an explicit nil
### GetPackageWeightUnit

`func (o *ProductCreate) GetPackageWeightUnit() string`

GetPackageWeightUnit returns the PackageWeightUnit field if non-nil, zero value otherwise.

### GetPackageWeightUnitOk

`func (o *ProductCreate) GetPackageWeightUnitOk() (*string, bool)`

GetPackageWeightUnitOk returns a tuple with the PackageWeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageWeightUnit

`func (o *ProductCreate) SetPackageWeightUnit(v string)`

SetPackageWeightUnit sets PackageWeightUnit field to given value.

### HasPackageWeightUnit

`func (o *ProductCreate) HasPackageWeightUnit() bool`

HasPackageWeightUnit returns a boolean if a field has been set.

### SetPackageWeightUnitNil

`func (o *ProductCreate) SetPackageWeightUnitNil(b bool)`

 SetPackageWeightUnitNil sets the value for PackageWeightUnit to be an explicit nil

### UnsetPackageWeightUnit
`func (o *ProductCreate) UnsetPackageWeightUnit()`

UnsetPackageWeightUnit ensures that no value is present for PackageWeightUnit, not even an explicit nil
### GetPackageWeightValue

`func (o *ProductCreate) GetPackageWeightValue() string`

GetPackageWeightValue returns the PackageWeightValue field if non-nil, zero value otherwise.

### GetPackageWeightValueOk

`func (o *ProductCreate) GetPackageWeightValueOk() (*string, bool)`

GetPackageWeightValueOk returns a tuple with the PackageWeightValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageWeightValue

`func (o *ProductCreate) SetPackageWeightValue(v string)`

SetPackageWeightValue sets PackageWeightValue field to given value.

### HasPackageWeightValue

`func (o *ProductCreate) HasPackageWeightValue() bool`

HasPackageWeightValue returns a boolean if a field has been set.

### SetPackageWeightValueNil

`func (o *ProductCreate) SetPackageWeightValueNil(b bool)`

 SetPackageWeightValueNil sets the value for PackageWeightValue to be an explicit nil

### UnsetPackageWeightValue
`func (o *ProductCreate) UnsetPackageWeightValue()`

UnsetPackageWeightValue ensures that no value is present for PackageWeightValue, not even an explicit nil
### GetPackageWidth

`func (o *ProductCreate) GetPackageWidth() string`

GetPackageWidth returns the PackageWidth field if non-nil, zero value otherwise.

### GetPackageWidthOk

`func (o *ProductCreate) GetPackageWidthOk() (*string, bool)`

GetPackageWidthOk returns a tuple with the PackageWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageWidth

`func (o *ProductCreate) SetPackageWidth(v string)`

SetPackageWidth sets PackageWidth field to given value.

### HasPackageWidth

`func (o *ProductCreate) HasPackageWidth() bool`

HasPackageWidth returns a boolean if a field has been set.

### SetPackageWidthNil

`func (o *ProductCreate) SetPackageWidthNil(b bool)`

 SetPackageWidthNil sets the value for PackageWidth to be an explicit nil

### UnsetPackageWidth
`func (o *ProductCreate) UnsetPackageWidth()`

UnsetPackageWidth ensures that no value is present for PackageWidth, not even an explicit nil
### GetProductCode

`func (o *ProductCreate) GetProductCode() string`

GetProductCode returns the ProductCode field if non-nil, zero value otherwise.

### GetProductCodeOk

`func (o *ProductCreate) GetProductCodeOk() (*string, bool)`

GetProductCodeOk returns a tuple with the ProductCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductCode

`func (o *ProductCreate) SetProductCode(v string)`

SetProductCode sets ProductCode field to given value.


### GetProductType

`func (o *ProductCreate) GetProductType() string`

GetProductType returns the ProductType field if non-nil, zero value otherwise.

### GetProductTypeOk

`func (o *ProductCreate) GetProductTypeOk() (*string, bool)`

GetProductTypeOk returns a tuple with the ProductType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductType

`func (o *ProductCreate) SetProductType(v string)`

SetProductType sets ProductType field to given value.

### HasProductType

`func (o *ProductCreate) HasProductType() bool`

HasProductType returns a boolean if a field has been set.

### SetProductTypeNil

`func (o *ProductCreate) SetProductTypeNil(b bool)`

 SetProductTypeNil sets the value for ProductType to be an explicit nil

### UnsetProductType
`func (o *ProductCreate) UnsetProductType()`

UnsetProductType ensures that no value is present for ProductType, not even an explicit nil
### GetPurchasePrice

`func (o *ProductCreate) GetPurchasePrice() string`

GetPurchasePrice returns the PurchasePrice field if non-nil, zero value otherwise.

### GetPurchasePriceOk

`func (o *ProductCreate) GetPurchasePriceOk() (*string, bool)`

GetPurchasePriceOk returns a tuple with the PurchasePrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurchasePrice

`func (o *ProductCreate) SetPurchasePrice(v string)`

SetPurchasePrice sets PurchasePrice field to given value.

### HasPurchasePrice

`func (o *ProductCreate) HasPurchasePrice() bool`

HasPurchasePrice returns a boolean if a field has been set.

### SetPurchasePriceNil

`func (o *ProductCreate) SetPurchasePriceNil(b bool)`

 SetPurchasePriceNil sets the value for PurchasePrice to be an explicit nil

### UnsetPurchasePrice
`func (o *ProductCreate) UnsetPurchasePrice()`

UnsetPurchasePrice ensures that no value is present for PurchasePrice, not even an explicit nil
### GetReorderQuantity

`func (o *ProductCreate) GetReorderQuantity() int64`

GetReorderQuantity returns the ReorderQuantity field if non-nil, zero value otherwise.

### GetReorderQuantityOk

`func (o *ProductCreate) GetReorderQuantityOk() (*int64, bool)`

GetReorderQuantityOk returns a tuple with the ReorderQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReorderQuantity

`func (o *ProductCreate) SetReorderQuantity(v int64)`

SetReorderQuantity sets ReorderQuantity field to given value.

### HasReorderQuantity

`func (o *ProductCreate) HasReorderQuantity() bool`

HasReorderQuantity returns a boolean if a field has been set.

### SetReorderQuantityNil

`func (o *ProductCreate) SetReorderQuantityNil(b bool)`

 SetReorderQuantityNil sets the value for ReorderQuantity to be an explicit nil

### UnsetReorderQuantity
`func (o *ProductCreate) UnsetReorderQuantity()`

UnsetReorderQuantity ensures that no value is present for ReorderQuantity, not even an explicit nil
### GetSalePrice

`func (o *ProductCreate) GetSalePrice() string`

GetSalePrice returns the SalePrice field if non-nil, zero value otherwise.

### GetSalePriceOk

`func (o *ProductCreate) GetSalePriceOk() (*string, bool)`

GetSalePriceOk returns a tuple with the SalePrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalePrice

`func (o *ProductCreate) SetSalePrice(v string)`

SetSalePrice sets SalePrice field to given value.

### HasSalePrice

`func (o *ProductCreate) HasSalePrice() bool`

HasSalePrice returns a boolean if a field has been set.

### SetSalePriceNil

`func (o *ProductCreate) SetSalePriceNil(b bool)`

 SetSalePriceNil sets the value for SalePrice to be an explicit nil

### UnsetSalePrice
`func (o *ProductCreate) UnsetSalePrice()`

UnsetSalePrice ensures that no value is present for SalePrice, not even an explicit nil
### GetShippingPrice

`func (o *ProductCreate) GetShippingPrice() string`

GetShippingPrice returns the ShippingPrice field if non-nil, zero value otherwise.

### GetShippingPriceOk

`func (o *ProductCreate) GetShippingPriceOk() (*string, bool)`

GetShippingPriceOk returns a tuple with the ShippingPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingPrice

`func (o *ProductCreate) SetShippingPrice(v string)`

SetShippingPrice sets ShippingPrice field to given value.

### HasShippingPrice

`func (o *ProductCreate) HasShippingPrice() bool`

HasShippingPrice returns a boolean if a field has been set.

### SetShippingPriceNil

`func (o *ProductCreate) SetShippingPriceNil(b bool)`

 SetShippingPriceNil sets the value for ShippingPrice to be an explicit nil

### UnsetShippingPrice
`func (o *ProductCreate) UnsetShippingPrice()`

UnsetShippingPrice ensures that no value is present for ShippingPrice, not even an explicit nil
### GetShippingRequiresInsurance

`func (o *ProductCreate) GetShippingRequiresInsurance() bool`

GetShippingRequiresInsurance returns the ShippingRequiresInsurance field if non-nil, zero value otherwise.

### GetShippingRequiresInsuranceOk

`func (o *ProductCreate) GetShippingRequiresInsuranceOk() (*bool, bool)`

GetShippingRequiresInsuranceOk returns a tuple with the ShippingRequiresInsurance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShippingRequiresInsurance

`func (o *ProductCreate) SetShippingRequiresInsurance(v bool)`

SetShippingRequiresInsurance sets ShippingRequiresInsurance field to given value.

### HasShippingRequiresInsurance

`func (o *ProductCreate) HasShippingRequiresInsurance() bool`

HasShippingRequiresInsurance returns a boolean if a field has been set.

### SetShippingRequiresInsuranceNil

`func (o *ProductCreate) SetShippingRequiresInsuranceNil(b bool)`

 SetShippingRequiresInsuranceNil sets the value for ShippingRequiresInsurance to be an explicit nil

### UnsetShippingRequiresInsurance
`func (o *ProductCreate) UnsetShippingRequiresInsurance()`

UnsetShippingRequiresInsurance ensures that no value is present for ShippingRequiresInsurance, not even an explicit nil
### GetSku

`func (o *ProductCreate) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *ProductCreate) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *ProductCreate) SetSku(v string)`

SetSku sets Sku field to given value.


### GetStockQuantity

`func (o *ProductCreate) GetStockQuantity() int64`

GetStockQuantity returns the StockQuantity field if non-nil, zero value otherwise.

### GetStockQuantityOk

`func (o *ProductCreate) GetStockQuantityOk() (*int64, bool)`

GetStockQuantityOk returns a tuple with the StockQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStockQuantity

`func (o *ProductCreate) SetStockQuantity(v int64)`

SetStockQuantity sets StockQuantity field to given value.

### HasStockQuantity

`func (o *ProductCreate) HasStockQuantity() bool`

HasStockQuantity returns a boolean if a field has been set.

### SetStockQuantityNil

`func (o *ProductCreate) SetStockQuantityNil(b bool)`

 SetStockQuantityNil sets the value for StockQuantity to be an explicit nil

### UnsetStockQuantity
`func (o *ProductCreate) UnsetStockQuantity()`

UnsetStockQuantity ensures that no value is present for StockQuantity, not even an explicit nil
### GetTags

`func (o *ProductCreate) GetTags() interface{}`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ProductCreate) GetTagsOk() (*interface{}, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ProductCreate) SetTags(v interface{})`

SetTags sets Tags field to given value.

### HasTags

`func (o *ProductCreate) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *ProductCreate) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *ProductCreate) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTaxPrice

`func (o *ProductCreate) GetTaxPrice() string`

GetTaxPrice returns the TaxPrice field if non-nil, zero value otherwise.

### GetTaxPriceOk

`func (o *ProductCreate) GetTaxPriceOk() (*string, bool)`

GetTaxPriceOk returns a tuple with the TaxPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxPrice

`func (o *ProductCreate) SetTaxPrice(v string)`

SetTaxPrice sets TaxPrice field to given value.

### HasTaxPrice

`func (o *ProductCreate) HasTaxPrice() bool`

HasTaxPrice returns a boolean if a field has been set.

### SetTaxPriceNil

`func (o *ProductCreate) SetTaxPriceNil(b bool)`

 SetTaxPriceNil sets the value for TaxPrice to be an explicit nil

### UnsetTaxPrice
`func (o *ProductCreate) UnsetTaxPrice()`

UnsetTaxPrice ensures that no value is present for TaxPrice, not even an explicit nil
### GetTrackBatch

`func (o *ProductCreate) GetTrackBatch() bool`

GetTrackBatch returns the TrackBatch field if non-nil, zero value otherwise.

### GetTrackBatchOk

`func (o *ProductCreate) GetTrackBatchOk() (*bool, bool)`

GetTrackBatchOk returns a tuple with the TrackBatch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackBatch

`func (o *ProductCreate) SetTrackBatch(v bool)`

SetTrackBatch sets TrackBatch field to given value.

### HasTrackBatch

`func (o *ProductCreate) HasTrackBatch() bool`

HasTrackBatch returns a boolean if a field has been set.

### GetTrackSerial

`func (o *ProductCreate) GetTrackSerial() bool`

GetTrackSerial returns the TrackSerial field if non-nil, zero value otherwise.

### GetTrackSerialOk

`func (o *ProductCreate) GetTrackSerialOk() (*bool, bool)`

GetTrackSerialOk returns a tuple with the TrackSerial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackSerial

`func (o *ProductCreate) SetTrackSerial(v bool)`

SetTrackSerial sets TrackSerial field to given value.

### HasTrackSerial

`func (o *ProductCreate) HasTrackSerial() bool`

HasTrackSerial returns a boolean if a field has been set.

### GetUnit

`func (o *ProductCreate) GetUnit() interface{}`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *ProductCreate) GetUnitOk() (*interface{}, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *ProductCreate) SetUnit(v interface{})`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *ProductCreate) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### SetUnitNil

`func (o *ProductCreate) SetUnitNil(b bool)`

 SetUnitNil sets the value for Unit to be an explicit nil

### UnsetUnit
`func (o *ProductCreate) UnsetUnit()`

UnsetUnit ensures that no value is present for Unit, not even an explicit nil
### GetWeightUnit

`func (o *ProductCreate) GetWeightUnit() string`

GetWeightUnit returns the WeightUnit field if non-nil, zero value otherwise.

### GetWeightUnitOk

`func (o *ProductCreate) GetWeightUnitOk() (*string, bool)`

GetWeightUnitOk returns a tuple with the WeightUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightUnit

`func (o *ProductCreate) SetWeightUnit(v string)`

SetWeightUnit sets WeightUnit field to given value.

### HasWeightUnit

`func (o *ProductCreate) HasWeightUnit() bool`

HasWeightUnit returns a boolean if a field has been set.

### SetWeightUnitNil

`func (o *ProductCreate) SetWeightUnitNil(b bool)`

 SetWeightUnitNil sets the value for WeightUnit to be an explicit nil

### UnsetWeightUnit
`func (o *ProductCreate) UnsetWeightUnit()`

UnsetWeightUnit ensures that no value is present for WeightUnit, not even an explicit nil
### GetWeightValue

`func (o *ProductCreate) GetWeightValue() string`

GetWeightValue returns the WeightValue field if non-nil, zero value otherwise.

### GetWeightValueOk

`func (o *ProductCreate) GetWeightValueOk() (*string, bool)`

GetWeightValueOk returns a tuple with the WeightValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeightValue

`func (o *ProductCreate) SetWeightValue(v string)`

SetWeightValue sets WeightValue field to given value.

### HasWeightValue

`func (o *ProductCreate) HasWeightValue() bool`

HasWeightValue returns a boolean if a field has been set.

### SetWeightValueNil

`func (o *ProductCreate) SetWeightValueNil(b bool)`

 SetWeightValueNil sets the value for WeightValue to be an explicit nil

### UnsetWeightValue
`func (o *ProductCreate) UnsetWeightValue()`

UnsetWeightValue ensures that no value is present for WeightValue, not even an explicit nil
### GetWidth

`func (o *ProductCreate) GetWidth() string`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *ProductCreate) GetWidthOk() (*string, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *ProductCreate) SetWidth(v string)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *ProductCreate) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### SetWidthNil

`func (o *ProductCreate) SetWidthNil(b bool)`

 SetWidthNil sets the value for Width to be an explicit nil

### UnsetWidth
`func (o *ProductCreate) UnsetWidth()`

UnsetWidth ensures that no value is present for Width, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


