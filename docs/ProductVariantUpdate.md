# ProductVariantUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Barcode** | Pointer to **NullableString** |  | [optional] 
**ImageLink** | Pointer to **NullableString** |  | [optional] 
**IsActive** | Pointer to **NullableBool** |  | [optional] 
**Name** | Pointer to **NullableString** | Human-readable variant label, e.g. \&quot;Red / M\&quot;. | [optional] 
**OptionValues** | Pointer to **interface{}** | Option name → value map, e.g. &#x60;{\&quot;Color\&quot;: \&quot;Red\&quot;, \&quot;Size\&quot;: \&quot;M\&quot;}&#x60;. | [optional] 
**Price** | Pointer to **NullableString** | Explicit override price for this variant (takes precedence over parent price + delta). | [optional] 
**PriceDelta** | Pointer to **NullableString** | Price adjustment relative to the parent product&#39;s &#x60;default_price&#x60;. | [optional] 
**ProductId** | Pointer to **NullableString** | The parent product this variant belongs to. References the product entity. | [optional] 
**Sku** | Pointer to **NullableString** | Variant-specific SKU (must be unique per tenant). | [optional] 
**StockQuantity** | Pointer to **NullableInt64** | Variant-level stock (optional — may be tracked on the parent only). | [optional] 

## Methods

### NewProductVariantUpdate

`func NewProductVariantUpdate() *ProductVariantUpdate`

NewProductVariantUpdate instantiates a new ProductVariantUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProductVariantUpdateWithDefaults

`func NewProductVariantUpdateWithDefaults() *ProductVariantUpdate`

NewProductVariantUpdateWithDefaults instantiates a new ProductVariantUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBarcode

`func (o *ProductVariantUpdate) GetBarcode() string`

GetBarcode returns the Barcode field if non-nil, zero value otherwise.

### GetBarcodeOk

`func (o *ProductVariantUpdate) GetBarcodeOk() (*string, bool)`

GetBarcodeOk returns a tuple with the Barcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBarcode

`func (o *ProductVariantUpdate) SetBarcode(v string)`

SetBarcode sets Barcode field to given value.

### HasBarcode

`func (o *ProductVariantUpdate) HasBarcode() bool`

HasBarcode returns a boolean if a field has been set.

### SetBarcodeNil

`func (o *ProductVariantUpdate) SetBarcodeNil(b bool)`

 SetBarcodeNil sets the value for Barcode to be an explicit nil

### UnsetBarcode
`func (o *ProductVariantUpdate) UnsetBarcode()`

UnsetBarcode ensures that no value is present for Barcode, not even an explicit nil
### GetImageLink

`func (o *ProductVariantUpdate) GetImageLink() string`

GetImageLink returns the ImageLink field if non-nil, zero value otherwise.

### GetImageLinkOk

`func (o *ProductVariantUpdate) GetImageLinkOk() (*string, bool)`

GetImageLinkOk returns a tuple with the ImageLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageLink

`func (o *ProductVariantUpdate) SetImageLink(v string)`

SetImageLink sets ImageLink field to given value.

### HasImageLink

`func (o *ProductVariantUpdate) HasImageLink() bool`

HasImageLink returns a boolean if a field has been set.

### SetImageLinkNil

`func (o *ProductVariantUpdate) SetImageLinkNil(b bool)`

 SetImageLinkNil sets the value for ImageLink to be an explicit nil

### UnsetImageLink
`func (o *ProductVariantUpdate) UnsetImageLink()`

UnsetImageLink ensures that no value is present for ImageLink, not even an explicit nil
### GetIsActive

`func (o *ProductVariantUpdate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *ProductVariantUpdate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *ProductVariantUpdate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *ProductVariantUpdate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### SetIsActiveNil

`func (o *ProductVariantUpdate) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *ProductVariantUpdate) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetName

`func (o *ProductVariantUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProductVariantUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProductVariantUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ProductVariantUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ProductVariantUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ProductVariantUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetOptionValues

`func (o *ProductVariantUpdate) GetOptionValues() interface{}`

GetOptionValues returns the OptionValues field if non-nil, zero value otherwise.

### GetOptionValuesOk

`func (o *ProductVariantUpdate) GetOptionValuesOk() (*interface{}, bool)`

GetOptionValuesOk returns a tuple with the OptionValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptionValues

`func (o *ProductVariantUpdate) SetOptionValues(v interface{})`

SetOptionValues sets OptionValues field to given value.

### HasOptionValues

`func (o *ProductVariantUpdate) HasOptionValues() bool`

HasOptionValues returns a boolean if a field has been set.

### SetOptionValuesNil

`func (o *ProductVariantUpdate) SetOptionValuesNil(b bool)`

 SetOptionValuesNil sets the value for OptionValues to be an explicit nil

### UnsetOptionValues
`func (o *ProductVariantUpdate) UnsetOptionValues()`

UnsetOptionValues ensures that no value is present for OptionValues, not even an explicit nil
### GetPrice

`func (o *ProductVariantUpdate) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ProductVariantUpdate) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ProductVariantUpdate) SetPrice(v string)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *ProductVariantUpdate) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### SetPriceNil

`func (o *ProductVariantUpdate) SetPriceNil(b bool)`

 SetPriceNil sets the value for Price to be an explicit nil

### UnsetPrice
`func (o *ProductVariantUpdate) UnsetPrice()`

UnsetPrice ensures that no value is present for Price, not even an explicit nil
### GetPriceDelta

`func (o *ProductVariantUpdate) GetPriceDelta() string`

GetPriceDelta returns the PriceDelta field if non-nil, zero value otherwise.

### GetPriceDeltaOk

`func (o *ProductVariantUpdate) GetPriceDeltaOk() (*string, bool)`

GetPriceDeltaOk returns a tuple with the PriceDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceDelta

`func (o *ProductVariantUpdate) SetPriceDelta(v string)`

SetPriceDelta sets PriceDelta field to given value.

### HasPriceDelta

`func (o *ProductVariantUpdate) HasPriceDelta() bool`

HasPriceDelta returns a boolean if a field has been set.

### SetPriceDeltaNil

`func (o *ProductVariantUpdate) SetPriceDeltaNil(b bool)`

 SetPriceDeltaNil sets the value for PriceDelta to be an explicit nil

### UnsetPriceDelta
`func (o *ProductVariantUpdate) UnsetPriceDelta()`

UnsetPriceDelta ensures that no value is present for PriceDelta, not even an explicit nil
### GetProductId

`func (o *ProductVariantUpdate) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *ProductVariantUpdate) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *ProductVariantUpdate) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *ProductVariantUpdate) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *ProductVariantUpdate) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *ProductVariantUpdate) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetSku

`func (o *ProductVariantUpdate) GetSku() string`

GetSku returns the Sku field if non-nil, zero value otherwise.

### GetSkuOk

`func (o *ProductVariantUpdate) GetSkuOk() (*string, bool)`

GetSkuOk returns a tuple with the Sku field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSku

`func (o *ProductVariantUpdate) SetSku(v string)`

SetSku sets Sku field to given value.

### HasSku

`func (o *ProductVariantUpdate) HasSku() bool`

HasSku returns a boolean if a field has been set.

### SetSkuNil

`func (o *ProductVariantUpdate) SetSkuNil(b bool)`

 SetSkuNil sets the value for Sku to be an explicit nil

### UnsetSku
`func (o *ProductVariantUpdate) UnsetSku()`

UnsetSku ensures that no value is present for Sku, not even an explicit nil
### GetStockQuantity

`func (o *ProductVariantUpdate) GetStockQuantity() int64`

GetStockQuantity returns the StockQuantity field if non-nil, zero value otherwise.

### GetStockQuantityOk

`func (o *ProductVariantUpdate) GetStockQuantityOk() (*int64, bool)`

GetStockQuantityOk returns a tuple with the StockQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStockQuantity

`func (o *ProductVariantUpdate) SetStockQuantity(v int64)`

SetStockQuantity sets StockQuantity field to given value.

### HasStockQuantity

`func (o *ProductVariantUpdate) HasStockQuantity() bool`

HasStockQuantity returns a boolean if a field has been set.

### SetStockQuantityNil

`func (o *ProductVariantUpdate) SetStockQuantityNil(b bool)`

 SetStockQuantityNil sets the value for StockQuantity to be an explicit nil

### UnsetStockQuantity
`func (o *ProductVariantUpdate) UnsetStockQuantity()`

UnsetStockQuantity ensures that no value is present for StockQuantity, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


