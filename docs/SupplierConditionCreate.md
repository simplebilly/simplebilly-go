# SupplierConditionCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | **string** | Currency for the minimum order value. | 
**DeliveryTerms** | Pointer to **NullableString** | Incoterms, e.g. \&quot;EXW\&quot;, \&quot;DAP\&quot;. | [optional] 
**EarlyPaymentDiscountPercent** | Pointer to **NullableString** | Early-payment discount percentage (Skonto), e.g. 2.0. | [optional] 
**IsDefault** | Pointer to **bool** | Is this the default condition for the supplier? | [optional] 
**MinimumOrderValue** | Pointer to **NullableString** | Minimum order value required for this supplier. | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**PaymentDueDays** | Pointer to **NullableInt32** | Number of days within which payment is due. | [optional] 
**PaymentTerms** | Pointer to **NullableString** | Payment terms, e.g. \&quot;14 Tage, 2% Skonto\&quot;. | [optional] 
**SupplierContactId** | **string** | The supplier this condition applies to (&#x60;contact_id&#x60;). References the supplier entity. | 
**SupplierName** | Pointer to **NullableString** | The name of the supplier, denormalized for easy listing. | [optional] 
**VolumeDiscountTiers** | Pointer to **interface{}** | Tiered discounts: JSON array of &#x60;{min_quantity, discount_percent}&#x60;. | [optional] 

## Methods

### NewSupplierConditionCreate

`func NewSupplierConditionCreate(currency string, supplierContactId string, ) *SupplierConditionCreate`

NewSupplierConditionCreate instantiates a new SupplierConditionCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupplierConditionCreateWithDefaults

`func NewSupplierConditionCreateWithDefaults() *SupplierConditionCreate`

NewSupplierConditionCreateWithDefaults instantiates a new SupplierConditionCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *SupplierConditionCreate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SupplierConditionCreate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SupplierConditionCreate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDeliveryTerms

`func (o *SupplierConditionCreate) GetDeliveryTerms() string`

GetDeliveryTerms returns the DeliveryTerms field if non-nil, zero value otherwise.

### GetDeliveryTermsOk

`func (o *SupplierConditionCreate) GetDeliveryTermsOk() (*string, bool)`

GetDeliveryTermsOk returns a tuple with the DeliveryTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryTerms

`func (o *SupplierConditionCreate) SetDeliveryTerms(v string)`

SetDeliveryTerms sets DeliveryTerms field to given value.

### HasDeliveryTerms

`func (o *SupplierConditionCreate) HasDeliveryTerms() bool`

HasDeliveryTerms returns a boolean if a field has been set.

### SetDeliveryTermsNil

`func (o *SupplierConditionCreate) SetDeliveryTermsNil(b bool)`

 SetDeliveryTermsNil sets the value for DeliveryTerms to be an explicit nil

### UnsetDeliveryTerms
`func (o *SupplierConditionCreate) UnsetDeliveryTerms()`

UnsetDeliveryTerms ensures that no value is present for DeliveryTerms, not even an explicit nil
### GetEarlyPaymentDiscountPercent

`func (o *SupplierConditionCreate) GetEarlyPaymentDiscountPercent() string`

GetEarlyPaymentDiscountPercent returns the EarlyPaymentDiscountPercent field if non-nil, zero value otherwise.

### GetEarlyPaymentDiscountPercentOk

`func (o *SupplierConditionCreate) GetEarlyPaymentDiscountPercentOk() (*string, bool)`

GetEarlyPaymentDiscountPercentOk returns a tuple with the EarlyPaymentDiscountPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEarlyPaymentDiscountPercent

`func (o *SupplierConditionCreate) SetEarlyPaymentDiscountPercent(v string)`

SetEarlyPaymentDiscountPercent sets EarlyPaymentDiscountPercent field to given value.

### HasEarlyPaymentDiscountPercent

`func (o *SupplierConditionCreate) HasEarlyPaymentDiscountPercent() bool`

HasEarlyPaymentDiscountPercent returns a boolean if a field has been set.

### SetEarlyPaymentDiscountPercentNil

`func (o *SupplierConditionCreate) SetEarlyPaymentDiscountPercentNil(b bool)`

 SetEarlyPaymentDiscountPercentNil sets the value for EarlyPaymentDiscountPercent to be an explicit nil

### UnsetEarlyPaymentDiscountPercent
`func (o *SupplierConditionCreate) UnsetEarlyPaymentDiscountPercent()`

UnsetEarlyPaymentDiscountPercent ensures that no value is present for EarlyPaymentDiscountPercent, not even an explicit nil
### GetIsDefault

`func (o *SupplierConditionCreate) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *SupplierConditionCreate) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *SupplierConditionCreate) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *SupplierConditionCreate) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.

### GetMinimumOrderValue

`func (o *SupplierConditionCreate) GetMinimumOrderValue() string`

GetMinimumOrderValue returns the MinimumOrderValue field if non-nil, zero value otherwise.

### GetMinimumOrderValueOk

`func (o *SupplierConditionCreate) GetMinimumOrderValueOk() (*string, bool)`

GetMinimumOrderValueOk returns a tuple with the MinimumOrderValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumOrderValue

`func (o *SupplierConditionCreate) SetMinimumOrderValue(v string)`

SetMinimumOrderValue sets MinimumOrderValue field to given value.

### HasMinimumOrderValue

`func (o *SupplierConditionCreate) HasMinimumOrderValue() bool`

HasMinimumOrderValue returns a boolean if a field has been set.

### SetMinimumOrderValueNil

`func (o *SupplierConditionCreate) SetMinimumOrderValueNil(b bool)`

 SetMinimumOrderValueNil sets the value for MinimumOrderValue to be an explicit nil

### UnsetMinimumOrderValue
`func (o *SupplierConditionCreate) UnsetMinimumOrderValue()`

UnsetMinimumOrderValue ensures that no value is present for MinimumOrderValue, not even an explicit nil
### GetNotes

`func (o *SupplierConditionCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *SupplierConditionCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *SupplierConditionCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *SupplierConditionCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *SupplierConditionCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *SupplierConditionCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPaymentDueDays

`func (o *SupplierConditionCreate) GetPaymentDueDays() int32`

GetPaymentDueDays returns the PaymentDueDays field if non-nil, zero value otherwise.

### GetPaymentDueDaysOk

`func (o *SupplierConditionCreate) GetPaymentDueDaysOk() (*int32, bool)`

GetPaymentDueDaysOk returns a tuple with the PaymentDueDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDueDays

`func (o *SupplierConditionCreate) SetPaymentDueDays(v int32)`

SetPaymentDueDays sets PaymentDueDays field to given value.

### HasPaymentDueDays

`func (o *SupplierConditionCreate) HasPaymentDueDays() bool`

HasPaymentDueDays returns a boolean if a field has been set.

### SetPaymentDueDaysNil

`func (o *SupplierConditionCreate) SetPaymentDueDaysNil(b bool)`

 SetPaymentDueDaysNil sets the value for PaymentDueDays to be an explicit nil

### UnsetPaymentDueDays
`func (o *SupplierConditionCreate) UnsetPaymentDueDays()`

UnsetPaymentDueDays ensures that no value is present for PaymentDueDays, not even an explicit nil
### GetPaymentTerms

`func (o *SupplierConditionCreate) GetPaymentTerms() string`

GetPaymentTerms returns the PaymentTerms field if non-nil, zero value otherwise.

### GetPaymentTermsOk

`func (o *SupplierConditionCreate) GetPaymentTermsOk() (*string, bool)`

GetPaymentTermsOk returns a tuple with the PaymentTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentTerms

`func (o *SupplierConditionCreate) SetPaymentTerms(v string)`

SetPaymentTerms sets PaymentTerms field to given value.

### HasPaymentTerms

`func (o *SupplierConditionCreate) HasPaymentTerms() bool`

HasPaymentTerms returns a boolean if a field has been set.

### SetPaymentTermsNil

`func (o *SupplierConditionCreate) SetPaymentTermsNil(b bool)`

 SetPaymentTermsNil sets the value for PaymentTerms to be an explicit nil

### UnsetPaymentTerms
`func (o *SupplierConditionCreate) UnsetPaymentTerms()`

UnsetPaymentTerms ensures that no value is present for PaymentTerms, not even an explicit nil
### GetSupplierContactId

`func (o *SupplierConditionCreate) GetSupplierContactId() string`

GetSupplierContactId returns the SupplierContactId field if non-nil, zero value otherwise.

### GetSupplierContactIdOk

`func (o *SupplierConditionCreate) GetSupplierContactIdOk() (*string, bool)`

GetSupplierContactIdOk returns a tuple with the SupplierContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierContactId

`func (o *SupplierConditionCreate) SetSupplierContactId(v string)`

SetSupplierContactId sets SupplierContactId field to given value.


### GetSupplierName

`func (o *SupplierConditionCreate) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *SupplierConditionCreate) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *SupplierConditionCreate) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.

### HasSupplierName

`func (o *SupplierConditionCreate) HasSupplierName() bool`

HasSupplierName returns a boolean if a field has been set.

### SetSupplierNameNil

`func (o *SupplierConditionCreate) SetSupplierNameNil(b bool)`

 SetSupplierNameNil sets the value for SupplierName to be an explicit nil

### UnsetSupplierName
`func (o *SupplierConditionCreate) UnsetSupplierName()`

UnsetSupplierName ensures that no value is present for SupplierName, not even an explicit nil
### GetVolumeDiscountTiers

`func (o *SupplierConditionCreate) GetVolumeDiscountTiers() interface{}`

GetVolumeDiscountTiers returns the VolumeDiscountTiers field if non-nil, zero value otherwise.

### GetVolumeDiscountTiersOk

`func (o *SupplierConditionCreate) GetVolumeDiscountTiersOk() (*interface{}, bool)`

GetVolumeDiscountTiersOk returns a tuple with the VolumeDiscountTiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolumeDiscountTiers

`func (o *SupplierConditionCreate) SetVolumeDiscountTiers(v interface{})`

SetVolumeDiscountTiers sets VolumeDiscountTiers field to given value.

### HasVolumeDiscountTiers

`func (o *SupplierConditionCreate) HasVolumeDiscountTiers() bool`

HasVolumeDiscountTiers returns a boolean if a field has been set.

### SetVolumeDiscountTiersNil

`func (o *SupplierConditionCreate) SetVolumeDiscountTiersNil(b bool)`

 SetVolumeDiscountTiersNil sets the value for VolumeDiscountTiers to be an explicit nil

### UnsetVolumeDiscountTiers
`func (o *SupplierConditionCreate) UnsetVolumeDiscountTiers()`

UnsetVolumeDiscountTiers ensures that no value is present for VolumeDiscountTiers, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


