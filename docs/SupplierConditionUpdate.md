# SupplierConditionUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **NullableString** | Currency for the minimum order value. | [optional] 
**DeliveryTerms** | Pointer to **NullableString** | Incoterms, e.g. \&quot;EXW\&quot;, \&quot;DAP\&quot;. | [optional] 
**EarlyPaymentDiscountPercent** | Pointer to **NullableString** | Early-payment discount percentage (Skonto), e.g. 2.0. | [optional] 
**IsDefault** | Pointer to **NullableBool** | Is this the default condition for the supplier? | [optional] 
**MinimumOrderValue** | Pointer to **NullableString** | Minimum order value required for this supplier. | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**PaymentDueDays** | Pointer to **NullableInt32** | Number of days within which payment is due. | [optional] 
**PaymentTerms** | Pointer to **NullableString** | Payment terms, e.g. \&quot;14 Tage, 2% Skonto\&quot;. | [optional] 
**SupplierContactId** | Pointer to **NullableString** | The supplier this condition applies to (&#x60;contact_id&#x60;). References the supplier entity. | [optional] 
**SupplierName** | Pointer to **NullableString** | The name of the supplier, denormalized for easy listing. | [optional] 
**VolumeDiscountTiers** | Pointer to **interface{}** | Tiered discounts: JSON array of &#x60;{min_quantity, discount_percent}&#x60;. | [optional] 

## Methods

### NewSupplierConditionUpdate

`func NewSupplierConditionUpdate() *SupplierConditionUpdate`

NewSupplierConditionUpdate instantiates a new SupplierConditionUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSupplierConditionUpdateWithDefaults

`func NewSupplierConditionUpdateWithDefaults() *SupplierConditionUpdate`

NewSupplierConditionUpdateWithDefaults instantiates a new SupplierConditionUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *SupplierConditionUpdate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SupplierConditionUpdate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SupplierConditionUpdate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *SupplierConditionUpdate) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *SupplierConditionUpdate) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *SupplierConditionUpdate) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetDeliveryTerms

`func (o *SupplierConditionUpdate) GetDeliveryTerms() string`

GetDeliveryTerms returns the DeliveryTerms field if non-nil, zero value otherwise.

### GetDeliveryTermsOk

`func (o *SupplierConditionUpdate) GetDeliveryTermsOk() (*string, bool)`

GetDeliveryTermsOk returns a tuple with the DeliveryTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryTerms

`func (o *SupplierConditionUpdate) SetDeliveryTerms(v string)`

SetDeliveryTerms sets DeliveryTerms field to given value.

### HasDeliveryTerms

`func (o *SupplierConditionUpdate) HasDeliveryTerms() bool`

HasDeliveryTerms returns a boolean if a field has been set.

### SetDeliveryTermsNil

`func (o *SupplierConditionUpdate) SetDeliveryTermsNil(b bool)`

 SetDeliveryTermsNil sets the value for DeliveryTerms to be an explicit nil

### UnsetDeliveryTerms
`func (o *SupplierConditionUpdate) UnsetDeliveryTerms()`

UnsetDeliveryTerms ensures that no value is present for DeliveryTerms, not even an explicit nil
### GetEarlyPaymentDiscountPercent

`func (o *SupplierConditionUpdate) GetEarlyPaymentDiscountPercent() string`

GetEarlyPaymentDiscountPercent returns the EarlyPaymentDiscountPercent field if non-nil, zero value otherwise.

### GetEarlyPaymentDiscountPercentOk

`func (o *SupplierConditionUpdate) GetEarlyPaymentDiscountPercentOk() (*string, bool)`

GetEarlyPaymentDiscountPercentOk returns a tuple with the EarlyPaymentDiscountPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEarlyPaymentDiscountPercent

`func (o *SupplierConditionUpdate) SetEarlyPaymentDiscountPercent(v string)`

SetEarlyPaymentDiscountPercent sets EarlyPaymentDiscountPercent field to given value.

### HasEarlyPaymentDiscountPercent

`func (o *SupplierConditionUpdate) HasEarlyPaymentDiscountPercent() bool`

HasEarlyPaymentDiscountPercent returns a boolean if a field has been set.

### SetEarlyPaymentDiscountPercentNil

`func (o *SupplierConditionUpdate) SetEarlyPaymentDiscountPercentNil(b bool)`

 SetEarlyPaymentDiscountPercentNil sets the value for EarlyPaymentDiscountPercent to be an explicit nil

### UnsetEarlyPaymentDiscountPercent
`func (o *SupplierConditionUpdate) UnsetEarlyPaymentDiscountPercent()`

UnsetEarlyPaymentDiscountPercent ensures that no value is present for EarlyPaymentDiscountPercent, not even an explicit nil
### GetIsDefault

`func (o *SupplierConditionUpdate) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *SupplierConditionUpdate) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *SupplierConditionUpdate) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *SupplierConditionUpdate) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.

### SetIsDefaultNil

`func (o *SupplierConditionUpdate) SetIsDefaultNil(b bool)`

 SetIsDefaultNil sets the value for IsDefault to be an explicit nil

### UnsetIsDefault
`func (o *SupplierConditionUpdate) UnsetIsDefault()`

UnsetIsDefault ensures that no value is present for IsDefault, not even an explicit nil
### GetMinimumOrderValue

`func (o *SupplierConditionUpdate) GetMinimumOrderValue() string`

GetMinimumOrderValue returns the MinimumOrderValue field if non-nil, zero value otherwise.

### GetMinimumOrderValueOk

`func (o *SupplierConditionUpdate) GetMinimumOrderValueOk() (*string, bool)`

GetMinimumOrderValueOk returns a tuple with the MinimumOrderValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumOrderValue

`func (o *SupplierConditionUpdate) SetMinimumOrderValue(v string)`

SetMinimumOrderValue sets MinimumOrderValue field to given value.

### HasMinimumOrderValue

`func (o *SupplierConditionUpdate) HasMinimumOrderValue() bool`

HasMinimumOrderValue returns a boolean if a field has been set.

### SetMinimumOrderValueNil

`func (o *SupplierConditionUpdate) SetMinimumOrderValueNil(b bool)`

 SetMinimumOrderValueNil sets the value for MinimumOrderValue to be an explicit nil

### UnsetMinimumOrderValue
`func (o *SupplierConditionUpdate) UnsetMinimumOrderValue()`

UnsetMinimumOrderValue ensures that no value is present for MinimumOrderValue, not even an explicit nil
### GetNotes

`func (o *SupplierConditionUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *SupplierConditionUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *SupplierConditionUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *SupplierConditionUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *SupplierConditionUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *SupplierConditionUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPaymentDueDays

`func (o *SupplierConditionUpdate) GetPaymentDueDays() int32`

GetPaymentDueDays returns the PaymentDueDays field if non-nil, zero value otherwise.

### GetPaymentDueDaysOk

`func (o *SupplierConditionUpdate) GetPaymentDueDaysOk() (*int32, bool)`

GetPaymentDueDaysOk returns a tuple with the PaymentDueDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDueDays

`func (o *SupplierConditionUpdate) SetPaymentDueDays(v int32)`

SetPaymentDueDays sets PaymentDueDays field to given value.

### HasPaymentDueDays

`func (o *SupplierConditionUpdate) HasPaymentDueDays() bool`

HasPaymentDueDays returns a boolean if a field has been set.

### SetPaymentDueDaysNil

`func (o *SupplierConditionUpdate) SetPaymentDueDaysNil(b bool)`

 SetPaymentDueDaysNil sets the value for PaymentDueDays to be an explicit nil

### UnsetPaymentDueDays
`func (o *SupplierConditionUpdate) UnsetPaymentDueDays()`

UnsetPaymentDueDays ensures that no value is present for PaymentDueDays, not even an explicit nil
### GetPaymentTerms

`func (o *SupplierConditionUpdate) GetPaymentTerms() string`

GetPaymentTerms returns the PaymentTerms field if non-nil, zero value otherwise.

### GetPaymentTermsOk

`func (o *SupplierConditionUpdate) GetPaymentTermsOk() (*string, bool)`

GetPaymentTermsOk returns a tuple with the PaymentTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentTerms

`func (o *SupplierConditionUpdate) SetPaymentTerms(v string)`

SetPaymentTerms sets PaymentTerms field to given value.

### HasPaymentTerms

`func (o *SupplierConditionUpdate) HasPaymentTerms() bool`

HasPaymentTerms returns a boolean if a field has been set.

### SetPaymentTermsNil

`func (o *SupplierConditionUpdate) SetPaymentTermsNil(b bool)`

 SetPaymentTermsNil sets the value for PaymentTerms to be an explicit nil

### UnsetPaymentTerms
`func (o *SupplierConditionUpdate) UnsetPaymentTerms()`

UnsetPaymentTerms ensures that no value is present for PaymentTerms, not even an explicit nil
### GetSupplierContactId

`func (o *SupplierConditionUpdate) GetSupplierContactId() string`

GetSupplierContactId returns the SupplierContactId field if non-nil, zero value otherwise.

### GetSupplierContactIdOk

`func (o *SupplierConditionUpdate) GetSupplierContactIdOk() (*string, bool)`

GetSupplierContactIdOk returns a tuple with the SupplierContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierContactId

`func (o *SupplierConditionUpdate) SetSupplierContactId(v string)`

SetSupplierContactId sets SupplierContactId field to given value.

### HasSupplierContactId

`func (o *SupplierConditionUpdate) HasSupplierContactId() bool`

HasSupplierContactId returns a boolean if a field has been set.

### SetSupplierContactIdNil

`func (o *SupplierConditionUpdate) SetSupplierContactIdNil(b bool)`

 SetSupplierContactIdNil sets the value for SupplierContactId to be an explicit nil

### UnsetSupplierContactId
`func (o *SupplierConditionUpdate) UnsetSupplierContactId()`

UnsetSupplierContactId ensures that no value is present for SupplierContactId, not even an explicit nil
### GetSupplierName

`func (o *SupplierConditionUpdate) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *SupplierConditionUpdate) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *SupplierConditionUpdate) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.

### HasSupplierName

`func (o *SupplierConditionUpdate) HasSupplierName() bool`

HasSupplierName returns a boolean if a field has been set.

### SetSupplierNameNil

`func (o *SupplierConditionUpdate) SetSupplierNameNil(b bool)`

 SetSupplierNameNil sets the value for SupplierName to be an explicit nil

### UnsetSupplierName
`func (o *SupplierConditionUpdate) UnsetSupplierName()`

UnsetSupplierName ensures that no value is present for SupplierName, not even an explicit nil
### GetVolumeDiscountTiers

`func (o *SupplierConditionUpdate) GetVolumeDiscountTiers() interface{}`

GetVolumeDiscountTiers returns the VolumeDiscountTiers field if non-nil, zero value otherwise.

### GetVolumeDiscountTiersOk

`func (o *SupplierConditionUpdate) GetVolumeDiscountTiersOk() (*interface{}, bool)`

GetVolumeDiscountTiersOk returns a tuple with the VolumeDiscountTiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolumeDiscountTiers

`func (o *SupplierConditionUpdate) SetVolumeDiscountTiers(v interface{})`

SetVolumeDiscountTiers sets VolumeDiscountTiers field to given value.

### HasVolumeDiscountTiers

`func (o *SupplierConditionUpdate) HasVolumeDiscountTiers() bool`

HasVolumeDiscountTiers returns a boolean if a field has been set.

### SetVolumeDiscountTiersNil

`func (o *SupplierConditionUpdate) SetVolumeDiscountTiersNil(b bool)`

 SetVolumeDiscountTiersNil sets the value for VolumeDiscountTiers to be an explicit nil

### UnsetVolumeDiscountTiers
`func (o *SupplierConditionUpdate) UnsetVolumeDiscountTiers()`

UnsetVolumeDiscountTiers ensures that no value is present for VolumeDiscountTiers, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


