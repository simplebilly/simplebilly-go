# RfqUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **NullableString** |  | [optional] 
**LineItems** | Pointer to **interface{}** | JSON array of &#x60;{product_id, name, sku, quantity, requested_unit_price?, quoted_unit_price?}&#x60;. | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**RequestedDate** | Pointer to **NullableString** |  | [optional] 
**ResponseDate** | Pointer to **NullableString** |  | [optional] 
**RfqNumber** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**NullableRfqStatus**](RfqStatus.md) | One of: draft | sent | offer_received | rejected | converted | [optional] 
**SupplierContactId** | Pointer to **NullableString** | References the supplier entity. | [optional] 
**SupplierName** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewRfqUpdate

`func NewRfqUpdate() *RfqUpdate`

NewRfqUpdate instantiates a new RfqUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRfqUpdateWithDefaults

`func NewRfqUpdateWithDefaults() *RfqUpdate`

NewRfqUpdateWithDefaults instantiates a new RfqUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *RfqUpdate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *RfqUpdate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *RfqUpdate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *RfqUpdate) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *RfqUpdate) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *RfqUpdate) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetLineItems

`func (o *RfqUpdate) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *RfqUpdate) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *RfqUpdate) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *RfqUpdate) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *RfqUpdate) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *RfqUpdate) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *RfqUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *RfqUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *RfqUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *RfqUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *RfqUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *RfqUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetRequestedDate

`func (o *RfqUpdate) GetRequestedDate() string`

GetRequestedDate returns the RequestedDate field if non-nil, zero value otherwise.

### GetRequestedDateOk

`func (o *RfqUpdate) GetRequestedDateOk() (*string, bool)`

GetRequestedDateOk returns a tuple with the RequestedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedDate

`func (o *RfqUpdate) SetRequestedDate(v string)`

SetRequestedDate sets RequestedDate field to given value.

### HasRequestedDate

`func (o *RfqUpdate) HasRequestedDate() bool`

HasRequestedDate returns a boolean if a field has been set.

### SetRequestedDateNil

`func (o *RfqUpdate) SetRequestedDateNil(b bool)`

 SetRequestedDateNil sets the value for RequestedDate to be an explicit nil

### UnsetRequestedDate
`func (o *RfqUpdate) UnsetRequestedDate()`

UnsetRequestedDate ensures that no value is present for RequestedDate, not even an explicit nil
### GetResponseDate

`func (o *RfqUpdate) GetResponseDate() string`

GetResponseDate returns the ResponseDate field if non-nil, zero value otherwise.

### GetResponseDateOk

`func (o *RfqUpdate) GetResponseDateOk() (*string, bool)`

GetResponseDateOk returns a tuple with the ResponseDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseDate

`func (o *RfqUpdate) SetResponseDate(v string)`

SetResponseDate sets ResponseDate field to given value.

### HasResponseDate

`func (o *RfqUpdate) HasResponseDate() bool`

HasResponseDate returns a boolean if a field has been set.

### SetResponseDateNil

`func (o *RfqUpdate) SetResponseDateNil(b bool)`

 SetResponseDateNil sets the value for ResponseDate to be an explicit nil

### UnsetResponseDate
`func (o *RfqUpdate) UnsetResponseDate()`

UnsetResponseDate ensures that no value is present for ResponseDate, not even an explicit nil
### GetRfqNumber

`func (o *RfqUpdate) GetRfqNumber() string`

GetRfqNumber returns the RfqNumber field if non-nil, zero value otherwise.

### GetRfqNumberOk

`func (o *RfqUpdate) GetRfqNumberOk() (*string, bool)`

GetRfqNumberOk returns a tuple with the RfqNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRfqNumber

`func (o *RfqUpdate) SetRfqNumber(v string)`

SetRfqNumber sets RfqNumber field to given value.

### HasRfqNumber

`func (o *RfqUpdate) HasRfqNumber() bool`

HasRfqNumber returns a boolean if a field has been set.

### SetRfqNumberNil

`func (o *RfqUpdate) SetRfqNumberNil(b bool)`

 SetRfqNumberNil sets the value for RfqNumber to be an explicit nil

### UnsetRfqNumber
`func (o *RfqUpdate) UnsetRfqNumber()`

UnsetRfqNumber ensures that no value is present for RfqNumber, not even an explicit nil
### GetStatus

`func (o *RfqUpdate) GetStatus() RfqStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RfqUpdate) GetStatusOk() (*RfqStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RfqUpdate) SetStatus(v RfqStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RfqUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *RfqUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *RfqUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetSupplierContactId

`func (o *RfqUpdate) GetSupplierContactId() string`

GetSupplierContactId returns the SupplierContactId field if non-nil, zero value otherwise.

### GetSupplierContactIdOk

`func (o *RfqUpdate) GetSupplierContactIdOk() (*string, bool)`

GetSupplierContactIdOk returns a tuple with the SupplierContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierContactId

`func (o *RfqUpdate) SetSupplierContactId(v string)`

SetSupplierContactId sets SupplierContactId field to given value.

### HasSupplierContactId

`func (o *RfqUpdate) HasSupplierContactId() bool`

HasSupplierContactId returns a boolean if a field has been set.

### SetSupplierContactIdNil

`func (o *RfqUpdate) SetSupplierContactIdNil(b bool)`

 SetSupplierContactIdNil sets the value for SupplierContactId to be an explicit nil

### UnsetSupplierContactId
`func (o *RfqUpdate) UnsetSupplierContactId()`

UnsetSupplierContactId ensures that no value is present for SupplierContactId, not even an explicit nil
### GetSupplierName

`func (o *RfqUpdate) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *RfqUpdate) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *RfqUpdate) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.

### HasSupplierName

`func (o *RfqUpdate) HasSupplierName() bool`

HasSupplierName returns a boolean if a field has been set.

### SetSupplierNameNil

`func (o *RfqUpdate) SetSupplierNameNil(b bool)`

 SetSupplierNameNil sets the value for SupplierName to be an explicit nil

### UnsetSupplierName
`func (o *RfqUpdate) UnsetSupplierName()`

UnsetSupplierName ensures that no value is present for SupplierName, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


