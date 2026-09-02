# GenerateVariantsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Options** | Pointer to **map[string][]string** | Option name → list of values, e.g. &#x60;{\&quot;Color\&quot;: [\&quot;Red\&quot;, \&quot;Blue\&quot;], \&quot;Size\&quot;: [\&quot;S\&quot;, \&quot;M\&quot;]}&#x60;. The cartesian product of these lists is generated. | [optional] 
**PriceDelta** | Pointer to **NullableString** | Optional per-variant price delta applied to every generated variant. | [optional] 
**ProductId** | **string** |  | 
**SkuPrefix** | Pointer to **NullableString** | Optional prefix for the generated SKUs (suffix is the option values joined by &#x60;-&#x60;). Falls back to the parent product&#39;s SKU. | [optional] 

## Methods

### NewGenerateVariantsRequest

`func NewGenerateVariantsRequest(productId string, ) *GenerateVariantsRequest`

NewGenerateVariantsRequest instantiates a new GenerateVariantsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGenerateVariantsRequestWithDefaults

`func NewGenerateVariantsRequestWithDefaults() *GenerateVariantsRequest`

NewGenerateVariantsRequestWithDefaults instantiates a new GenerateVariantsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOptions

`func (o *GenerateVariantsRequest) GetOptions() map[string][]string`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *GenerateVariantsRequest) GetOptionsOk() (*map[string][]string, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *GenerateVariantsRequest) SetOptions(v map[string][]string)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *GenerateVariantsRequest) HasOptions() bool`

HasOptions returns a boolean if a field has been set.

### GetPriceDelta

`func (o *GenerateVariantsRequest) GetPriceDelta() string`

GetPriceDelta returns the PriceDelta field if non-nil, zero value otherwise.

### GetPriceDeltaOk

`func (o *GenerateVariantsRequest) GetPriceDeltaOk() (*string, bool)`

GetPriceDeltaOk returns a tuple with the PriceDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceDelta

`func (o *GenerateVariantsRequest) SetPriceDelta(v string)`

SetPriceDelta sets PriceDelta field to given value.

### HasPriceDelta

`func (o *GenerateVariantsRequest) HasPriceDelta() bool`

HasPriceDelta returns a boolean if a field has been set.

### SetPriceDeltaNil

`func (o *GenerateVariantsRequest) SetPriceDeltaNil(b bool)`

 SetPriceDeltaNil sets the value for PriceDelta to be an explicit nil

### UnsetPriceDelta
`func (o *GenerateVariantsRequest) UnsetPriceDelta()`

UnsetPriceDelta ensures that no value is present for PriceDelta, not even an explicit nil
### GetProductId

`func (o *GenerateVariantsRequest) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *GenerateVariantsRequest) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *GenerateVariantsRequest) SetProductId(v string)`

SetProductId sets ProductId field to given value.


### GetSkuPrefix

`func (o *GenerateVariantsRequest) GetSkuPrefix() string`

GetSkuPrefix returns the SkuPrefix field if non-nil, zero value otherwise.

### GetSkuPrefixOk

`func (o *GenerateVariantsRequest) GetSkuPrefixOk() (*string, bool)`

GetSkuPrefixOk returns a tuple with the SkuPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkuPrefix

`func (o *GenerateVariantsRequest) SetSkuPrefix(v string)`

SetSkuPrefix sets SkuPrefix field to given value.

### HasSkuPrefix

`func (o *GenerateVariantsRequest) HasSkuPrefix() bool`

HasSkuPrefix returns a boolean if a field has been set.

### SetSkuPrefixNil

`func (o *GenerateVariantsRequest) SetSkuPrefixNil(b bool)`

 SetSkuPrefixNil sets the value for SkuPrefix to be an explicit nil

### UnsetSkuPrefix
`func (o *GenerateVariantsRequest) UnsetSkuPrefix()`

UnsetSkuPrefix ensures that no value is present for SkuPrefix, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


