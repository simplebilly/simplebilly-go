# ProductVariantCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Barcode** | Pointer to **NullableString** |  | [optional] 
**ImageLink** | Pointer to **NullableString** |  | [optional] 
**IsActive** | Pointer to **bool** |  | [optional] 
**Name** | Pointer to **NullableString** | Human-readable variant label, e.g. \&quot;Red / M\&quot;. | [optional] 
**OptionValues** | Pointer to **interface{}** | Option name → value map, e.g. &#x60;{\&quot;Color\&quot;: \&quot;Red\&quot;, \&quot;Size\&quot;: \&quot;M\&quot;}&#x60;. | [optional] 
**Price** | Pointer to **NullableString** | Explicit override price for this variant (takes precedence over parent price + delta). | [optional] 
**PriceDelta** | Pointer to **NullableString** | Price adjustment relative to the parent product&#39;s &#x60;default_price&#x60;. | [optional] 
**ProductId** | **string** | The parent product this variant belongs to. References the product entity. | 
**Sku** | **string** | Variant-specific SKU (must be unique per tenant). | 
**StockQuantity** | Pointer to **NullableInt64** | Variant-level stock (optional — may be tracked on the parent only). | [optional] 

## Methods

### NewProductVariantCreate

`func NewProductVariantCreate(productId string, sku string, ) *ProductVariantCreate`

NewProductVariantCreate instantiates a new ProductVariantCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductVariantCreateWithDefaults

`func NewProductVariantCreateWithDefaults() *ProductVariantCreate`

NewProductVariantCreateWithDefaults instantiates a new ProductVariantCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBarcode

`func (o *ProductVariantCreate) GetBarcode() string`

GetBarcode returns the Barcode field if non-nil, zero value otherwise.

### GetBarcodeOk

`func (o *ProductVariantCreate) GetBarcodeOk() (*string, bool)`

GetBarcodeOk returns a tuple with the Barcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBarcode

`func (o *ProductVariantCreate) SetBarcode(v string)`

SetBarcode sets Barcode field to given value.

### HasBarcode

`func (o *ProductVariantCreate) HasBarcode() bool`

HasBarcode returns a boolean if a field has been set.

### SetBarcodeNil

`func (o *ProductVariantCreate) SetBarcodeNil(b bool)`

 SetBarcodeNil sets the value for Barcode to be an explicit nil

### UnsetBarcode
`func (o *ProductVariantCreate) UnsetBarcode()`

UnsetBarcode ensures that no value is present for Barcode, not even an explicit nil
### GetImageLink

`func (o *ProductVariantCreate) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *ProductVariantCreate) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *ProductVariantCreate) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *ProductVariantCreate) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### SetImageLinkNil

`func (o *ProductVariantCreate) SetImageLinkNil(b bool)`

 SetImageLinkNil sets the value for ImageLink to be an explicit nil

### UnsetImageLink
`func (o *ProductVariantCreate) UnsetImageLink()`

UnsetImageLink ensures that no value is present for ImageLink, not even an explicit nil
### GetIsActive

`func (o *ProductVariantCreate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *ProductVariantCreate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *ProductVariantCreate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *ProductVariantCreate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetName

`func (o *ProductVariantCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductVariantCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductVariantCreate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductVariantCreate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ProductVariantCreate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ProductVariantCreate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetOptionValues

`func (o *ProductVariantCreate) GetOptionValues() interface{}`

GetOptionValues returns the OptionValues field if non-nil, zero value otherwise.

### GetOptionValuesOk

`func (o *ProductVariantCreate) GetOptionValuesOk() (*interface{}, bool)`

GetOptionValuesOk returns a tuple with the OptionValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptionValues

`func (o *ProductVariantCreate) SetOptionValues(v interface{})`

SetOptionValues sets OptionValues field to given value.

### HasOptionValues

`func (o *ProductVariantCreate) HasOptionValues() bool`

HasOptionValues returns a boolean if a field has been set.

### SetOptionValuesNil

`func (o *ProductVariantCreate) SetOptionValuesNil(b bool)`

 SetOptionValuesNil sets the value for OptionValues to be an explicit nil

### UnsetOptionValues
`func (o *ProductVariantCreate) UnsetOptionValues()`

UnsetOptionValues ensures that no value is present for OptionValues, not even an explicit nil
### GetPrice

`func (o *ProductVariantCreate) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ProductVariantCreate) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ProductVariantCreate) SetPrice(v string)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *ProductVariantCreate) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### SetPriceNil

`func (o *ProductVariantCreate) SetPriceNil(b bool)`

 SetPriceNil sets the value for Price to be an explicit nil

### UnsetPrice
`func (o *ProductVariantCreate) UnsetPrice()`

UnsetPrice ensures that no value is present for Price, not even an explicit nil
### GetPriceDelta

`func (o *ProductVariantCreate) GetPriceDelta() string`

GetPriceDelta returns the PriceDelta field if non-nil, zero value otherwise.

### GetPriceDeltaOk

`func (o *ProductVariantCreate) GetPriceDeltaOk() (*string, bool)`

GetPriceDeltaOk returns a tuple with the PriceDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceDelta

`func (o *ProductVariantCreate) SetPriceDelta(v string)`

SetPriceDelta sets PriceDelta field to given value.

### HasPriceDelta

`func (o *ProductVariantCreate) HasPriceDelta() bool`

HasPriceDelta returns a boolean if a field has been set.

### SetPriceDeltaNil

`func (o *ProductVariantCreate) SetPriceDeltaNil(b bool)`

 SetPriceDeltaNil sets the value for PriceDelta to be an explicit nil

### UnsetPriceDelta
`func (o *ProductVariantCreate) UnsetPriceDelta()`

UnsetPriceDelta ensures that no value is present for PriceDelta, not even an explicit nil
### GetProductId

`func (o *ProductVariantCreate) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ProductVariantCreate) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ProductVariantCreate) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetSku

`func (o *ProductVariantCreate) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *ProductVariantCreate) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *ProductVariantCreate) SetSku(v string)`

SetSku sets Sku field to given value.


### GetStockQuantity

`func (o *ProductVariantCreate) GetStockQuantity() int64`

GetStockQuantity returns the StockQuantity field if non-nil, zero value otherwise.

### GetStockQuantityOk

`func (o *ProductVariantCreate) GetStockQuantityOk() (*int64, bool)`

GetStockQuantityOk returns a tuple with the StockQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStockQuantity

`func (o *ProductVariantCreate) SetStockQuantity(v int64)`

SetStockQuantity sets StockQuantity field to given value.

### HasStockQuantity

`func (o *ProductVariantCreate) HasStockQuantity() bool`

HasStockQuantity returns a boolean if a field has been set.

### SetStockQuantityNil

`func (o *ProductVariantCreate) SetStockQuantityNil(b bool)`

 SetStockQuantityNil sets the value for StockQuantity to be an explicit nil

### UnsetStockQuantity
`func (o *ProductVariantCreate) UnsetStockQuantity()`

UnsetStockQuantity ensures that no value is present for StockQuantity, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


