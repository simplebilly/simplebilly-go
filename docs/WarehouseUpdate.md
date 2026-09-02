# WarehouseUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressCity** | Pointer to **NullableString** |  | [optional] 
**AddressCountry** | Pointer to [**NullableCountryCode**](CountryCode.md) |  | [optional] 
**AddressStreet** | Pointer to **NullableString** |  | [optional] 
**AddressZip** | Pointer to **NullableString** |  | [optional] 
**BinLocations** | Pointer to **interface{}** | JSON array of bin locations, e.g. &#x60;[\&quot;A-01-01\&quot;, \&quot;A-01-02\&quot;]&#x60;. | [optional] 
**Code** | Pointer to **NullableString** |  | [optional] 
**IsActive** | Pointer to **NullableBool** |  | [optional] 
**IsDefault** | Pointer to **NullableBool** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewWarehouseUpdate

`func NewWarehouseUpdate() *WarehouseUpdate`

NewWarehouseUpdate instantiates a new WarehouseUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWarehouseUpdateWithDefaults

`func NewWarehouseUpdateWithDefaults() *WarehouseUpdate`

NewWarehouseUpdateWithDefaults instantiates a new WarehouseUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressCity

`func (o *WarehouseUpdate) GetAddressCity() string`

GetAddressCity returns the AddressCity field if non-nil, zero value otherwise.

### GetAddressCityOk

`func (o *WarehouseUpdate) GetAddressCityOk() (*string, bool)`

GetAddressCityOk returns a tuple with the AddressCity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressCity

`func (o *WarehouseUpdate) SetAddressCity(v string)`

SetAddressCity sets AddressCity field to given value.

### HasAddressCity

`func (o *WarehouseUpdate) HasAddressCity() bool`

HasAddressCity returns a boolean if a field has been set.

### SetAddressCityNil

`func (o *WarehouseUpdate) SetAddressCityNil(b bool)`

 SetAddressCityNil sets the value for AddressCity to be an explicit nil

### UnsetAddressCity
`func (o *WarehouseUpdate) UnsetAddressCity()`

UnsetAddressCity ensures that no value is present for AddressCity, not even an explicit nil
### GetAddressCountry

`func (o *WarehouseUpdate) GetAddressCountry() CountryCode`

GetAddressCountry returns the AddressCountry field if non-nil, zero value otherwise.

### GetAddressCountryOk

`func (o *WarehouseUpdate) GetAddressCountryOk() (*CountryCode, bool)`

GetAddressCountryOk returns a tuple with the AddressCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressCountry

`func (o *WarehouseUpdate) SetAddressCountry(v CountryCode)`

SetAddressCountry sets AddressCountry field to given value.

### HasAddressCountry

`func (o *WarehouseUpdate) HasAddressCountry() bool`

HasAddressCountry returns a boolean if a field has been set.

### SetAddressCountryNil

`func (o *WarehouseUpdate) SetAddressCountryNil(b bool)`

 SetAddressCountryNil sets the value for AddressCountry to be an explicit nil

### UnsetAddressCountry
`func (o *WarehouseUpdate) UnsetAddressCountry()`

UnsetAddressCountry ensures that no value is present for AddressCountry, not even an explicit nil
### GetAddressStreet

`func (o *WarehouseUpdate) GetAddressStreet() string`

GetAddressStreet returns the AddressStreet field if non-nil, zero value otherwise.

### GetAddressStreetOk

`func (o *WarehouseUpdate) GetAddressStreetOk() (*string, bool)`

GetAddressStreetOk returns a tuple with the AddressStreet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressStreet

`func (o *WarehouseUpdate) SetAddressStreet(v string)`

SetAddressStreet sets AddressStreet field to given value.

### HasAddressStreet

`func (o *WarehouseUpdate) HasAddressStreet() bool`

HasAddressStreet returns a boolean if a field has been set.

### SetAddressStreetNil

`func (o *WarehouseUpdate) SetAddressStreetNil(b bool)`

 SetAddressStreetNil sets the value for AddressStreet to be an explicit nil

### UnsetAddressStreet
`func (o *WarehouseUpdate) UnsetAddressStreet()`

UnsetAddressStreet ensures that no value is present for AddressStreet, not even an explicit nil
### GetAddressZip

`func (o *WarehouseUpdate) GetAddressZip() string`

GetAddressZip returns the AddressZip field if non-nil, zero value otherwise.

### GetAddressZipOk

`func (o *WarehouseUpdate) GetAddressZipOk() (*string, bool)`

GetAddressZipOk returns a tuple with the AddressZip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressZip

`func (o *WarehouseUpdate) SetAddressZip(v string)`

SetAddressZip sets AddressZip field to given value.

### HasAddressZip

`func (o *WarehouseUpdate) HasAddressZip() bool`

HasAddressZip returns a boolean if a field has been set.

### SetAddressZipNil

`func (o *WarehouseUpdate) SetAddressZipNil(b bool)`

 SetAddressZipNil sets the value for AddressZip to be an explicit nil

### UnsetAddressZip
`func (o *WarehouseUpdate) UnsetAddressZip()`

UnsetAddressZip ensures that no value is present for AddressZip, not even an explicit nil
### GetBinLocations

`func (o *WarehouseUpdate) GetBinLocations() interface{}`

GetBinLocations returns the BinLocations field if non-nil, zero value otherwise.

### GetBinLocationsOk

`func (o *WarehouseUpdate) GetBinLocationsOk() (*interface{}, bool)`

GetBinLocationsOk returns a tuple with the BinLocations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBinLocations

`func (o *WarehouseUpdate) SetBinLocations(v interface{})`

SetBinLocations sets BinLocations field to given value.

### HasBinLocations

`func (o *WarehouseUpdate) HasBinLocations() bool`

HasBinLocations returns a boolean if a field has been set.

### SetBinLocationsNil

`func (o *WarehouseUpdate) SetBinLocationsNil(b bool)`

 SetBinLocationsNil sets the value for BinLocations to be an explicit nil

### UnsetBinLocations
`func (o *WarehouseUpdate) UnsetBinLocations()`

UnsetBinLocations ensures that no value is present for BinLocations, not even an explicit nil
### GetCode

`func (o *WarehouseUpdate) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *WarehouseUpdate) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *WarehouseUpdate) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *WarehouseUpdate) HasCode() bool`

HasCode returns a boolean if a field has been set.

### SetCodeNil

`func (o *WarehouseUpdate) SetCodeNil(b bool)`

 SetCodeNil sets the value for Code to be an explicit nil

### UnsetCode
`func (o *WarehouseUpdate) UnsetCode()`

UnsetCode ensures that no value is present for Code, not even an explicit nil
### GetIsActive

`func (o *WarehouseUpdate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *WarehouseUpdate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *WarehouseUpdate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *WarehouseUpdate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### SetIsActiveNil

`func (o *WarehouseUpdate) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *WarehouseUpdate) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetIsDefault

`func (o *WarehouseUpdate) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *WarehouseUpdate) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *WarehouseUpdate) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *WarehouseUpdate) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.

### SetIsDefaultNil

`func (o *WarehouseUpdate) SetIsDefaultNil(b bool)`

 SetIsDefaultNil sets the value for IsDefault to be an explicit nil

### UnsetIsDefault
`func (o *WarehouseUpdate) UnsetIsDefault()`

UnsetIsDefault ensures that no value is present for IsDefault, not even an explicit nil
### GetName

`func (o *WarehouseUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WarehouseUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WarehouseUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *WarehouseUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *WarehouseUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *WarehouseUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetNotes

`func (o *WarehouseUpdate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *WarehouseUpdate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *WarehouseUpdate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *WarehouseUpdate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *WarehouseUpdate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *WarehouseUpdate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


