# Rfq

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **string** |  | [optional] 
**LineItems** | **interface{}** | JSON array of &#x60;{product_id, name, sku, quantity, requested_unit_price?, quoted_unit_price?}&#x60;. | 
**Notes** | Pointer to **NullableString** |  | [optional] 
**RequestedDate** | **string** |  | 
**ResponseDate** | Pointer to **NullableString** |  | [optional] 
**RfqNumber** | **string** |  | 
**Status** | [**RfqStatus**](RfqStatus.md) | One of: draft | sent | offer_received | rejected | converted | 
**SupplierContactId** | Pointer to **NullableString** | References the supplier entity. | [optional] 
**SupplierName** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewRfq

`func NewRfq(lineItems interface{}, requestedDate string, rfqNumber string, status RfqStatus, ) *Rfq`

NewRfq instantiates a new Rfq object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRfqWithDefaults

`func NewRfqWithDefaults() *Rfq`

NewRfqWithDefaults instantiates a new Rfq object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *Rfq) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Rfq) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Rfq) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *Rfq) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetLineItems

`func (o *Rfq) GetLineItems() interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *Rfq) GetLineItemsOk() (*interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *Rfq) SetLineItems(v interface{})`

SetLineItems sets LineItems field to given value.


### SetLineItemsNil

`func (o *Rfq) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *Rfq) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetNotes

`func (o *Rfq) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *Rfq) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *Rfq) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *Rfq) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *Rfq) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *Rfq) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetRequestedDate

`func (o *Rfq) GetRequestedDate() string`

GetRequestedDate returns the RequestedDate field if non-nil, zero value otherwise.

### GetRequestedDateOk

`func (o *Rfq) GetRequestedDateOk() (*string, bool)`

GetRequestedDateOk returns a tuple with the RequestedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedDate

`func (o *Rfq) SetRequestedDate(v string)`

SetRequestedDate sets RequestedDate field to given value.


### GetResponseDate

`func (o *Rfq) GetResponseDate() string`

GetResponseDate returns the ResponseDate field if non-nil, zero value otherwise.

### GetResponseDateOk

`func (o *Rfq) GetResponseDateOk() (*string, bool)`

GetResponseDateOk returns a tuple with the ResponseDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponseDate

`func (o *Rfq) SetResponseDate(v string)`

SetResponseDate sets ResponseDate field to given value.

### HasResponseDate

`func (o *Rfq) HasResponseDate() bool`

HasResponseDate returns a boolean if a field has been set.

### SetResponseDateNil

`func (o *Rfq) SetResponseDateNil(b bool)`

 SetResponseDateNil sets the value for ResponseDate to be an explicit nil

### UnsetResponseDate
`func (o *Rfq) UnsetResponseDate()`

UnsetResponseDate ensures that no value is present for ResponseDate, not even an explicit nil
### GetRfqNumber

`func (o *Rfq) GetRfqNumber() string`

GetRfqNumber returns the RfqNumber field if non-nil, zero value otherwise.

### GetRfqNumberOk

`func (o *Rfq) GetRfqNumberOk() (*string, bool)`

GetRfqNumberOk returns a tuple with the RfqNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRfqNumber

`func (o *Rfq) SetRfqNumber(v string)`

SetRfqNumber sets RfqNumber field to given value.


### GetStatus

`func (o *Rfq) GetStatus() RfqStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Rfq) GetStatusOk() (*RfqStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Rfq) SetStatus(v RfqStatus)`

SetStatus sets Status field to given value.


### GetSupplierContactId

`func (o *Rfq) GetSupplierContactId() string`

GetSupplierContactId returns the SupplierContactId field if non-nil, zero value otherwise.

### GetSupplierContactIdOk

`func (o *Rfq) GetSupplierContactIdOk() (*string, bool)`

GetSupplierContactIdOk returns a tuple with the SupplierContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierContactId

`func (o *Rfq) SetSupplierContactId(v string)`

SetSupplierContactId sets SupplierContactId field to given value.

### HasSupplierContactId

`func (o *Rfq) HasSupplierContactId() bool`

HasSupplierContactId returns a boolean if a field has been set.

### SetSupplierContactIdNil

`func (o *Rfq) SetSupplierContactIdNil(b bool)`

 SetSupplierContactIdNil sets the value for SupplierContactId to be an explicit nil

### UnsetSupplierContactId
`func (o *Rfq) UnsetSupplierContactId()`

UnsetSupplierContactId ensures that no value is present for SupplierContactId, not even an explicit nil
### GetSupplierName

`func (o *Rfq) GetSupplierName() string`

GetSupplierName returns the SupplierName field if non-nil, zero value otherwise.

### GetSupplierNameOk

`func (o *Rfq) GetSupplierNameOk() (*string, bool)`

GetSupplierNameOk returns a tuple with the SupplierName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierName

`func (o *Rfq) SetSupplierName(v string)`

SetSupplierName sets SupplierName field to given value.

### HasSupplierName

`func (o *Rfq) HasSupplierName() bool`

HasSupplierName returns a boolean if a field has been set.

### SetSupplierNameNil

`func (o *Rfq) SetSupplierNameNil(b bool)`

 SetSupplierNameNil sets the value for SupplierName to be an explicit nil

### UnsetSupplierName
`func (o *Rfq) UnsetSupplierName()`

UnsetSupplierName ensures that no value is present for SupplierName, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


