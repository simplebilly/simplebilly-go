# WarehouseCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressCity** | Pointer to **NullableString** |  | [optional] 
**AddressCountry** | Pointer to [**NullableCountryCode**](CountryCode.md) |  | [optional] 
**AddressStreet** | Pointer to **NullableString** |  | [optional] 
**AddressZip** | Pointer to **NullableString** |  | [optional] 
**BinLocations** | Pointer to **interface{}** | JSON array of bin locations, e.g. &#x60;[\&quot;A-01-01\&quot;, \&quot;A-01-02\&quot;]&#x60;. | [optional] 
**Code** | **string** |  | 
**IsActive** | Pointer to **bool** |  | [optional] 
**IsDefault** | Pointer to **bool** |  | [optional] 
**Name** | **string** |  | 
**Notes** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewWarehouseCreate

`func NewWarehouseCreate(code string, name string, ) *WarehouseCreate`

NewWarehouseCreate instantiates a new WarehouseCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWarehouseCreateWithDefaults

`func NewWarehouseCreateWithDefaults() *WarehouseCreate`

NewWarehouseCreateWithDefaults instantiates a new WarehouseCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddressCity

`func (o *WarehouseCreate) GetAddressCity() string`

GetAddressCity returns the AddressCity field if non-nil, zero value otherwise.

### GetAddressCityOk

`func (o *WarehouseCreate) GetAddressCityOk() (*string, bool)`

GetAddressCityOk returns a tuple with the AddressCity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressCity

`func (o *WarehouseCreate) SetAddressCity(v string)`

SetAddressCity sets AddressCity field to given value.

### HasAddressCity

`func (o *WarehouseCreate) HasAddressCity() bool`

HasAddressCity returns a boolean if a field has been set.

### SetAddressCityNil

`func (o *WarehouseCreate) SetAddressCityNil(b bool)`

 SetAddressCityNil sets the value for AddressCity to be an explicit nil

### UnsetAddressCity
`func (o *WarehouseCreate) UnsetAddressCity()`

UnsetAddressCity ensures that no value is present for AddressCity, not even an explicit nil
### GetAddressCountry

`func (o *WarehouseCreate) GetAddressCountry() CountryCode`

GetAddressCountry returns the AddressCountry field if non-nil, zero value otherwise.

### GetAddressCountryOk

`func (o *WarehouseCreate) GetAddressCountryOk() (*CountryCode, bool)`

GetAddressCountryOk returns a tuple with the AddressCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressCountry

`func (o *WarehouseCreate) SetAddressCountry(v CountryCode)`

SetAddressCountry sets AddressCountry field to given value.

### HasAddressCountry

`func (o *WarehouseCreate) HasAddressCountry() bool`

HasAddressCountry returns a boolean if a field has been set.

### SetAddressCountryNil

`func (o *WarehouseCreate) SetAddressCountryNil(b bool)`

 SetAddressCountryNil sets the value for AddressCountry to be an explicit nil

### UnsetAddressCountry
`func (o *WarehouseCreate) UnsetAddressCountry()`

UnsetAddressCountry ensures that no value is present for AddressCountry, not even an explicit nil
### GetAddressStreet

`func (o *WarehouseCreate) GetAddressStreet() string`

GetAddressStreet returns the AddressStreet field if non-nil, zero value otherwise.

### GetAddressStreetOk

`func (o *WarehouseCreate) GetAddressStreetOk() (*string, bool)`

GetAddressStreetOk returns a tuple with the AddressStreet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressStreet

`func (o *WarehouseCreate) SetAddressStreet(v string)`

SetAddressStreet sets AddressStreet field to given value.

### HasAddressStreet

`func (o *WarehouseCreate) HasAddressStreet() bool`

HasAddressStreet returns a boolean if a field has been set.

### SetAddressStreetNil

`func (o *WarehouseCreate) SetAddressStreetNil(b bool)`

 SetAddressStreetNil sets the value for AddressStreet to be an explicit nil

### UnsetAddressStreet
`func (o *WarehouseCreate) UnsetAddressStreet()`

UnsetAddressStreet ensures that no value is present for AddressStreet, not even an explicit nil
### GetAddressZip

`func (o *WarehouseCreate) GetAddressZip() string`

GetAddressZip returns the AddressZip field if non-nil, zero value otherwise.

### GetAddressZipOk

`func (o *WarehouseCreate) GetAddressZipOk() (*string, bool)`

GetAddressZipOk returns a tuple with the AddressZip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressZip

`func (o *WarehouseCreate) SetAddressZip(v string)`

SetAddressZip sets AddressZip field to given value.

### HasAddressZip

`func (o *WarehouseCreate) HasAddressZip() bool`

HasAddressZip returns a boolean if a field has been set.

### SetAddressZipNil

`func (o *WarehouseCreate) SetAddressZipNil(b bool)`

 SetAddressZipNil sets the value for AddressZip to be an explicit nil

### UnsetAddressZip
`func (o *WarehouseCreate) UnsetAddressZip()`

UnsetAddressZip ensures that no value is present for AddressZip, not even an explicit nil
### GetBinLocations

`func (o *WarehouseCreate) GetBinLocations() interface{}`

GetBinLocations returns the BinLocations field if non-nil, zero value otherwise.

### GetBinLocationsOk

`func (o *WarehouseCreate) GetBinLocationsOk() (*interface{}, bool)`

GetBinLocationsOk returns a tuple with the BinLocations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBinLocations

`func (o *WarehouseCreate) SetBinLocations(v interface{})`

SetBinLocations sets BinLocations field to given value.

### HasBinLocations

`func (o *WarehouseCreate) HasBinLocations() bool`

HasBinLocations returns a boolean if a field has been set.

### SetBinLocationsNil

`func (o *WarehouseCreate) SetBinLocationsNil(b bool)`

 SetBinLocationsNil sets the value for BinLocations to be an explicit nil

### UnsetBinLocations
`func (o *WarehouseCreate) UnsetBinLocations()`

UnsetBinLocations ensures that no value is present for BinLocations, not even an explicit nil
### GetCode

`func (o *WarehouseCreate) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *WarehouseCreate) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *WarehouseCreate) SetCode(v string)`

SetCode sets Code field to given value.


### GetIsActive

`func (o *WarehouseCreate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *WarehouseCreate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *WarehouseCreate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *WarehouseCreate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetIsDefault

`func (o *WarehouseCreate) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *WarehouseCreate) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *WarehouseCreate) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *WarehouseCreate) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.

### GetName

`func (o *WarehouseCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WarehouseCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WarehouseCreate) SetName(v string)`

SetName sets Name field to given value.


### GetNotes

`func (o *WarehouseCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *WarehouseCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *WarehouseCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *WarehouseCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *WarehouseCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *WarehouseCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


