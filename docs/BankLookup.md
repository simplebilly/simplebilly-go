# BankLookup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BankName** | Pointer to **NullableString** |  | [optional] 
**Bic** | Pointer to **NullableString** |  | [optional] 
**Iban** | **string** |  | 
**Nextgenpsd2Url** | Pointer to **NullableString** |  | [optional] 
**Psd2Supported** | **bool** |  | 

## Methods

### NewBankLookup

`func NewBankLookup(iban string, psd2Supported bool, ) *BankLookup`

NewBankLookup instantiates a new BankLookup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBankLookupWithDefaults

`func NewBankLookupWithDefaults() *BankLookup`

NewBankLookupWithDefaults instantiates a new BankLookup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBankName

`func (o *BankLookup) GetBankName() string`

GetBankName returns the BankName field if non-nil, zero value otherwise.

### GetBankNameOk

`func (o *BankLookup) GetBankNameOk() (*string, bool)`

GetBankNameOk returns a tuple with the BankName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankName

`func (o *BankLookup) SetBankName(v string)`

SetBankName sets BankName field to given value.

### HasBankName

`func (o *BankLookup) HasBankName() bool`

HasBankName returns a boolean if a field has been set.

### SetBankNameNil

`func (o *BankLookup) SetBankNameNil(b bool)`

 SetBankNameNil sets the value for BankName to be an explicit nil

### UnsetBankName
`func (o *BankLookup) UnsetBankName()`

UnsetBankName ensures that no value is present for BankName, not even an explicit nil
### GetBic

`func (o *BankLookup) GetBic() string`

GetBic returns the Bic field if non-nil, zero value otherwise.

### GetBicOk

`func (o *BankLookup) GetBicOk() (*string, bool)`

GetBicOk returns a tuple with the Bic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBic

`func (o *BankLookup) SetBic(v string)`

SetBic sets Bic field to given value.

### HasBic

`func (o *BankLookup) HasBic() bool`

HasBic returns a boolean if a field has been set.

### SetBicNil

`func (o *BankLookup) SetBicNil(b bool)`

 SetBicNil sets the value for Bic to be an explicit nil

### UnsetBic
`func (o *BankLookup) UnsetBic()`

UnsetBic ensures that no value is present for Bic, not even an explicit nil
### GetIban

`func (o *BankLookup) GetIban() string`

GetIban returns the Iban field if non-nil, zero value otherwise.

### GetIbanOk

`func (o *BankLookup) GetIbanOk() (*string, bool)`

GetIbanOk returns a tuple with the Iban field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIban

`func (o *BankLookup) SetIban(v string)`

SetIban sets Iban field to given value.


### GetNextgenpsd2Url

`func (o *BankLookup) GetNextgenpsd2Url() string`

GetNextgenpsd2Url returns the Nextgenpsd2Url field if non-nil, zero value otherwise.

### GetNextgenpsd2UrlOk

`func (o *BankLookup) GetNextgenpsd2UrlOk() (*string, bool)`

GetNextgenpsd2UrlOk returns a tuple with the Nextgenpsd2Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextgenpsd2Url

`func (o *BankLookup) SetNextgenpsd2Url(v string)`

SetNextgenpsd2Url sets Nextgenpsd2Url field to given value.

### HasNextgenpsd2Url

`func (o *BankLookup) HasNextgenpsd2Url() bool`

HasNextgenpsd2Url returns a boolean if a field has been set.

### SetNextgenpsd2UrlNil

`func (o *BankLookup) SetNextgenpsd2UrlNil(b bool)`

 SetNextgenpsd2UrlNil sets the value for Nextgenpsd2Url to be an explicit nil

### UnsetNextgenpsd2Url
`func (o *BankLookup) UnsetNextgenpsd2Url()`

UnsetNextgenpsd2Url ensures that no value is present for Nextgenpsd2Url, not even an explicit nil
### GetPsd2Supported

`func (o *BankLookup) GetPsd2Supported() bool`

GetPsd2Supported returns the Psd2Supported field if non-nil, zero value otherwise.

### GetPsd2SupportedOk

`func (o *BankLookup) GetPsd2SupportedOk() (*bool, bool)`

GetPsd2SupportedOk returns a tuple with the Psd2Supported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPsd2Supported

`func (o *BankLookup) SetPsd2Supported(v bool)`

SetPsd2Supported sets Psd2Supported field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


