# Shareholder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **string** | Anschrift des Aktionärs (§ 67 Abs. 1 AktG). | [optional] 
**BirthDate** | Pointer to **NullableString** | Geburtsdatum des Aktionärs (§ 67 Abs. 1 AktG). | [optional] 
**Email** | Pointer to **string** | Elektronische Adresse (E-Mail) für die Kommunikation der Gesellschaft. | [optional] 
**FirstName** | Pointer to **string** | Vorname des Aktionärs (§ 67 Abs. 1 AktG). | [optional] 
**LastName** | Pointer to **string** | Nachname des Aktionärs (§ 67 Abs. 1 AktG). | [optional] 
**ShareNumber** | Pointer to **NullableString** | Aktiennummer bzw. Sammelurkunde (bei Nennbetragsaktien). | [optional] 
**Shares** | Pointer to **string** | Stückzahl der gehaltenen Stückaktien (§ 67 Abs. 1 AktG). | [optional] 

## Methods

### NewShareholder

`func NewShareholder() *Shareholder`

NewShareholder instantiates a new Shareholder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShareholderWithDefaults

`func NewShareholderWithDefaults() *Shareholder`

NewShareholderWithDefaults instantiates a new Shareholder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *Shareholder) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *Shareholder) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *Shareholder) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *Shareholder) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetBirthDate

`func (o *Shareholder) GetBirthDate() string`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *Shareholder) GetBirthDateOk() (*string, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *Shareholder) SetBirthDate(v string)`

SetBirthDate sets BirthDate field to given value.

### HasBirthDate

`func (o *Shareholder) HasBirthDate() bool`

HasBirthDate returns a boolean if a field has been set.

### SetBirthDateNil

`func (o *Shareholder) SetBirthDateNil(b bool)`

 SetBirthDateNil sets the value for BirthDate to be an explicit nil

### UnsetBirthDate
`func (o *Shareholder) UnsetBirthDate()`

UnsetBirthDate ensures that no value is present for BirthDate, not even an explicit nil
### GetEmail

`func (o *Shareholder) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *Shareholder) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *Shareholder) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *Shareholder) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetFirstName

`func (o *Shareholder) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *Shareholder) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *Shareholder) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *Shareholder) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *Shareholder) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *Shareholder) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *Shareholder) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *Shareholder) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetShareNumber

`func (o *Shareholder) GetShareNumber() string`

GetShareNumber returns the ShareNumber field if non-nil, zero value otherwise.

### GetShareNumberOk

`func (o *Shareholder) GetShareNumberOk() (*string, bool)`

GetShareNumberOk returns a tuple with the ShareNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShareNumber

`func (o *Shareholder) SetShareNumber(v string)`

SetShareNumber sets ShareNumber field to given value.

### HasShareNumber

`func (o *Shareholder) HasShareNumber() bool`

HasShareNumber returns a boolean if a field has been set.

### SetShareNumberNil

`func (o *Shareholder) SetShareNumberNil(b bool)`

 SetShareNumberNil sets the value for ShareNumber to be an explicit nil

### UnsetShareNumber
`func (o *Shareholder) UnsetShareNumber()`

UnsetShareNumber ensures that no value is present for ShareNumber, not even an explicit nil
### GetShares

`func (o *Shareholder) GetShares() string`

GetShares returns the Shares field if non-nil, zero value otherwise.

### GetSharesOk

`func (o *Shareholder) GetSharesOk() (*string, bool)`

GetSharesOk returns a tuple with the Shares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShares

`func (o *Shareholder) SetShares(v string)`

SetShares sets Shares field to given value.

### HasShares

`func (o *Shareholder) HasShares() bool`

HasShares returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


