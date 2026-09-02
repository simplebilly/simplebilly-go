# ShareholderCreate

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

### NewShareholderCreate

`func NewShareholderCreate() *ShareholderCreate`

NewShareholderCreate instantiates a new ShareholderCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShareholderCreateWithDefaults

`func NewShareholderCreateWithDefaults() *ShareholderCreate`

NewShareholderCreateWithDefaults instantiates a new ShareholderCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *ShareholderCreate) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ShareholderCreate) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ShareholderCreate) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *ShareholderCreate) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetBirthDate

`func (o *ShareholderCreate) GetBirthDate() string`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *ShareholderCreate) GetBirthDateOk() (*string, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *ShareholderCreate) SetBirthDate(v string)`

SetBirthDate sets BirthDate field to given value.

### HasBirthDate

`func (o *ShareholderCreate) HasBirthDate() bool`

HasBirthDate returns a boolean if a field has been set.

### SetBirthDateNil

`func (o *ShareholderCreate) SetBirthDateNil(b bool)`

 SetBirthDateNil sets the value for BirthDate to be an explicit nil

### UnsetBirthDate
`func (o *ShareholderCreate) UnsetBirthDate()`

UnsetBirthDate ensures that no value is present for BirthDate, not even an explicit nil
### GetEmail

`func (o *ShareholderCreate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *ShareholderCreate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *ShareholderCreate) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *ShareholderCreate) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetFirstName

`func (o *ShareholderCreate) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *ShareholderCreate) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *ShareholderCreate) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *ShareholderCreate) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *ShareholderCreate) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *ShareholderCreate) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *ShareholderCreate) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *ShareholderCreate) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetShareNumber

`func (o *ShareholderCreate) GetShareNumber() string`

GetShareNumber returns the ShareNumber field if non-nil, zero value otherwise.

### GetShareNumberOk

`func (o *ShareholderCreate) GetShareNumberOk() (*string, bool)`

GetShareNumberOk returns a tuple with the ShareNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShareNumber

`func (o *ShareholderCreate) SetShareNumber(v string)`

SetShareNumber sets ShareNumber field to given value.

### HasShareNumber

`func (o *ShareholderCreate) HasShareNumber() bool`

HasShareNumber returns a boolean if a field has been set.

### SetShareNumberNil

`func (o *ShareholderCreate) SetShareNumberNil(b bool)`

 SetShareNumberNil sets the value for ShareNumber to be an explicit nil

### UnsetShareNumber
`func (o *ShareholderCreate) UnsetShareNumber()`

UnsetShareNumber ensures that no value is present for ShareNumber, not even an explicit nil
### GetShares

`func (o *ShareholderCreate) GetShares() string`

GetShares returns the Shares field if non-nil, zero value otherwise.

### GetSharesOk

`func (o *ShareholderCreate) GetSharesOk() (*string, bool)`

GetSharesOk returns a tuple with the Shares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShares

`func (o *ShareholderCreate) SetShares(v string)`

SetShares sets Shares field to given value.

### HasShares

`func (o *ShareholderCreate) HasShares() bool`

HasShares returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


