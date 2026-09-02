# ShareholderUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **NullableString** | Anschrift des Aktionärs (§ 67 Abs. 1 AktG). | [optional] 
**BirthDate** | Pointer to **NullableString** | Geburtsdatum des Aktionärs (§ 67 Abs. 1 AktG). | [optional] 
**Email** | Pointer to **NullableString** | Elektronische Adresse (E-Mail) für die Kommunikation der Gesellschaft. | [optional] 
**FirstName** | Pointer to **NullableString** | Vorname des Aktionärs (§ 67 Abs. 1 AktG). | [optional] 
**LastName** | Pointer to **NullableString** | Nachname des Aktionärs (§ 67 Abs. 1 AktG). | [optional] 
**ShareNumber** | Pointer to **NullableString** | Aktiennummer bzw. Sammelurkunde (bei Nennbetragsaktien). | [optional] 
**Shares** | Pointer to **NullableString** | Stückzahl der gehaltenen Stückaktien (§ 67 Abs. 1 AktG). | [optional] 

## Methods

### NewShareholderUpdate

`func NewShareholderUpdate() *ShareholderUpdate`

NewShareholderUpdate instantiates a new ShareholderUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShareholderUpdateWithDefaults

`func NewShareholderUpdateWithDefaults() *ShareholderUpdate`

NewShareholderUpdateWithDefaults instantiates a new ShareholderUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *ShareholderUpdate) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ShareholderUpdate) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ShareholderUpdate) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *ShareholderUpdate) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *ShareholderUpdate) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *ShareholderUpdate) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetBirthDate

`func (o *ShareholderUpdate) GetBirthDate() string`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *ShareholderUpdate) GetBirthDateOk() (*string, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *ShareholderUpdate) SetBirthDate(v string)`

SetBirthDate sets BirthDate field to given value.

### HasBirthDate

`func (o *ShareholderUpdate) HasBirthDate() bool`

HasBirthDate returns a boolean if a field has been set.

### SetBirthDateNil

`func (o *ShareholderUpdate) SetBirthDateNil(b bool)`

 SetBirthDateNil sets the value for BirthDate to be an explicit nil

### UnsetBirthDate
`func (o *ShareholderUpdate) UnsetBirthDate()`

UnsetBirthDate ensures that no value is present for BirthDate, not even an explicit nil
### GetEmail

`func (o *ShareholderUpdate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *ShareholderUpdate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *ShareholderUpdate) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *ShareholderUpdate) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *ShareholderUpdate) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *ShareholderUpdate) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetFirstName

`func (o *ShareholderUpdate) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *ShareholderUpdate) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *ShareholderUpdate) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *ShareholderUpdate) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### SetFirstNameNil

`func (o *ShareholderUpdate) SetFirstNameNil(b bool)`

 SetFirstNameNil sets the value for FirstName to be an explicit nil

### UnsetFirstName
`func (o *ShareholderUpdate) UnsetFirstName()`

UnsetFirstName ensures that no value is present for FirstName, not even an explicit nil
### GetLastName

`func (o *ShareholderUpdate) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *ShareholderUpdate) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *ShareholderUpdate) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *ShareholderUpdate) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### SetLastNameNil

`func (o *ShareholderUpdate) SetLastNameNil(b bool)`

 SetLastNameNil sets the value for LastName to be an explicit nil

### UnsetLastName
`func (o *ShareholderUpdate) UnsetLastName()`

UnsetLastName ensures that no value is present for LastName, not even an explicit nil
### GetShareNumber

`func (o *ShareholderUpdate) GetShareNumber() string`

GetShareNumber returns the ShareNumber field if non-nil, zero value otherwise.

### GetShareNumberOk

`func (o *ShareholderUpdate) GetShareNumberOk() (*string, bool)`

GetShareNumberOk returns a tuple with the ShareNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShareNumber

`func (o *ShareholderUpdate) SetShareNumber(v string)`

SetShareNumber sets ShareNumber field to given value.

### HasShareNumber

`func (o *ShareholderUpdate) HasShareNumber() bool`

HasShareNumber returns a boolean if a field has been set.

### SetShareNumberNil

`func (o *ShareholderUpdate) SetShareNumberNil(b bool)`

 SetShareNumberNil sets the value for ShareNumber to be an explicit nil

### UnsetShareNumber
`func (o *ShareholderUpdate) UnsetShareNumber()`

UnsetShareNumber ensures that no value is present for ShareNumber, not even an explicit nil
### GetShares

`func (o *ShareholderUpdate) GetShares() string`

GetShares returns the Shares field if non-nil, zero value otherwise.

### GetSharesOk

`func (o *ShareholderUpdate) GetSharesOk() (*string, bool)`

GetSharesOk returns a tuple with the Shares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShares

`func (o *ShareholderUpdate) SetShares(v string)`

SetShares sets Shares field to given value.

### HasShares

`func (o *ShareholderUpdate) HasShares() bool`

HasShares returns a boolean if a field has been set.

### SetSharesNil

`func (o *ShareholderUpdate) SetSharesNil(b bool)`

 SetSharesNil sets the value for Shares to be an explicit nil

### UnsetShares
`func (o *ShareholderUpdate) UnsetShares()`

UnsetShares ensures that no value is present for Shares, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


